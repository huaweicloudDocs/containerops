# API概览<a name="ops_02_0006"></a>

通过使用ContainerOps提供的接口，您可以完整的使用ContainerOps的所有功能，包括创建流水线组、创建流水线等。

<a name="table636420173499"></a>
<table><thead align="left"><tr id="row1936421713499"><th class="cellrowborder" valign="top" width="32%" id="mcps1.1.3.1.1"><p id="p036401754914"><a name="p036401754914"></a><a name="p036401754914"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="68%" id="mcps1.1.3.1.2"><p id="p1364917154914"><a name="p1364917154914"></a><a name="p1364917154914"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row1636416178493"><td class="cellrowborder" valign="top" width="32%" headers="mcps1.1.3.1.1 "><p id="p7364717114914"><a name="p7364717114914"></a><a name="p7364717114914"></a><a href="#section14967428145618">流水线组管理</a></p>
</td>
<td class="cellrowborder" valign="top" width="68%" headers="mcps1.1.3.1.2 "><p id="p19208131145113"><a name="p19208131145113"></a><a name="p19208131145113"></a>流水线组管理接口，包括创建流水线组接口、获取流水组列表接口。</p>
</td>
</tr>
<tr id="row936591714910"><td class="cellrowborder" valign="top" width="32%" headers="mcps1.1.3.1.1 "><p id="p2036571717494"><a name="p2036571717494"></a><a name="p2036571717494"></a><a href="#section93712595412">流水线管理</a></p>
</td>
<td class="cellrowborder" valign="top" width="68%" headers="mcps1.1.3.1.2 "><p id="p14872144045215"><a name="p14872144045215"></a><a name="p14872144045215"></a>流水线管理接口，包括创建、更新、删除流水线的接口等。</p>
<p id="p145655559492"><a name="p145655559492"></a><a name="p145655559492"></a>通过这些接口，您可以创建、更新、删除流水线，查询流水线详情、列表，Webhook触发流水线或执行步骤，获取执行步骤的执行历史、执行日志，重试或回滚执行步骤，配置执行步骤的执行信息。</p>
</td>
</tr>
<tr id="row117561319151617"><td class="cellrowborder" valign="top" width="32%" headers="mcps1.1.3.1.1 "><p id="p575761991614"><a name="p575761991614"></a><a name="p575761991614"></a><a href="#section11826708186">软件包管理</a></p>
</td>
<td class="cellrowborder" valign="top" width="68%" headers="mcps1.1.3.1.2 "><p id="p1033772413167"><a name="p1033772413167"></a><a name="p1033772413167"></a>软件包管理接口，包括获取软件包列表、获取软件包版本的文件列表、下载文件的接口等。</p>
</td>
</tr>
</tbody>
</table>

## 流水线组管理接口<a name="section14967428145618"></a>

流水线组管理接口，包括创建流水线组接口、获取流水组列表接口。

**表 1**  流水线组管理接口

<a name="table334371126"></a>
<table><thead align="left"><tr id="row2344515214"><th class="cellrowborder" valign="top" width="32%" id="mcps1.2.3.1.1"><p id="p1534413111219"><a name="p1534413111219"></a><a name="p1534413111219"></a>API</p>
</th>
<th class="cellrowborder" valign="top" width="68%" id="mcps1.2.3.1.2"><p id="p103441811121"><a name="p103441811121"></a><a name="p103441811121"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row183441814213"><td class="cellrowborder" valign="top" width="32%" headers="mcps1.2.3.1.1 "><p id="p6948192055511"><a name="p6948192055511"></a><a name="p6948192055511"></a><a href="创建流水线组.md">创建流水线组</a></p>
</td>
<td class="cellrowborder" valign="top" width="68%" headers="mcps1.2.3.1.2 "><p id="p129481120135515"><a name="p129481120135515"></a><a name="p129481120135515"></a>创建流水线组。</p>
</td>
</tr>
<tr id="row18270148155414"><td class="cellrowborder" valign="top" width="32%" headers="mcps1.2.3.1.1 "><p id="p727113816547"><a name="p727113816547"></a><a name="p727113816547"></a><a href="删除流水线组.md">删除流水线组</a></p>
</td>
<td class="cellrowborder" valign="top" width="68%" headers="mcps1.2.3.1.2 "><p id="p627115817549"><a name="p627115817549"></a><a name="p627115817549"></a>删除指定的流水线组。</p>
</td>
</tr>
<tr id="row334491828"><td class="cellrowborder" valign="top" width="32%" headers="mcps1.2.3.1.1 "><p id="p11948132045512"><a name="p11948132045512"></a><a name="p11948132045512"></a><a href="获取流水线组列表.md">获取流水线组列表</a></p>
</td>
<td class="cellrowborder" valign="top" width="68%" headers="mcps1.2.3.1.2 "><p id="p5864133125718"><a name="p5864133125718"></a><a name="p5864133125718"></a>获取流水线组列表。</p>
</td>
</tr>
</tbody>
</table>

## 流水线管理接口<a name="section93712595412"></a>

流水线管理接口，包括创建、更新、删除流水线的接口等。通过这些接口，您可以创建、更新、删除流水线，查询流水线详情、列表，Webhook触发流水线或执行步骤，获取执行步骤的执行历史、执行日志等。

**表 2**  流水线管理接口

<a name="table3948152085517"></a>
<table><thead align="left"><tr id="row10948102065520"><th class="cellrowborder" valign="top" width="32.16%" id="mcps1.2.3.1.1"><p id="p2315132745517"><a name="p2315132745517"></a><a name="p2315132745517"></a>API</p>
</th>
<th class="cellrowborder" valign="top" width="67.84%" id="mcps1.2.3.1.2"><p id="p39484208554"><a name="p39484208554"></a><a name="p39484208554"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row2094832015553"><td class="cellrowborder" valign="top" width="32.16%" headers="mcps1.2.3.1.1 "><p id="p5948112012554"><a name="p5948112012554"></a><a name="p5948112012554"></a><a href="获取流水线模板列表.md">获取流水线模板列表</a></p>
</td>
<td class="cellrowborder" valign="top" width="67.84%" headers="mcps1.2.3.1.2 "><p id="p678314635718"><a name="p678314635718"></a><a name="p678314635718"></a>获取流水线模板列表。</p>
</td>
</tr>
<tr id="row8948142055510"><td class="cellrowborder" valign="top" width="32.16%" headers="mcps1.2.3.1.1 "><p id="p17948420155512"><a name="p17948420155512"></a><a name="p17948420155512"></a><a href="获取流水线模板详情.md">获取流水线模板详情</a></p>
</td>
<td class="cellrowborder" valign="top" width="67.84%" headers="mcps1.2.3.1.2 "><p id="p6844129145715"><a name="p6844129145715"></a><a name="p6844129145715"></a>获取流水线模板详情，包括<span>模板id</span>、<span>流水线前置操作</span>、<span>执行步骤</span>、<span>中文描述</span>、英文描述等。</p>
</td>
</tr>
<tr id="row1794817201555"><td class="cellrowborder" valign="top" width="32.16%" headers="mcps1.2.3.1.1 "><p id="p99481320155518"><a name="p99481320155518"></a><a name="p99481320155518"></a><a href="创建流水线.md">创建流水线</a></p>
</td>
<td class="cellrowborder" valign="top" width="67.84%" headers="mcps1.2.3.1.2 "><p id="p152546123570"><a name="p152546123570"></a><a name="p152546123570"></a>创建流水线。</p>
</td>
</tr>
<tr id="row19481020185511"><td class="cellrowborder" valign="top" width="32.16%" headers="mcps1.2.3.1.1 "><p id="p12948152045517"><a name="p12948152045517"></a><a name="p12948152045517"></a><a href="更新流水线.md">更新流水线</a></p>
</td>
<td class="cellrowborder" valign="top" width="67.84%" headers="mcps1.2.3.1.2 "><p id="p14464515155713"><a name="p14464515155713"></a><a name="p14464515155713"></a>更新流水线。</p>
</td>
</tr>
<tr id="row59482205557"><td class="cellrowborder" valign="top" width="32.16%" headers="mcps1.2.3.1.1 "><p id="p0950192020556"><a name="p0950192020556"></a><a name="p0950192020556"></a><a href="删除流水线.md">删除流水线</a></p>
</td>
<td class="cellrowborder" valign="top" width="67.84%" headers="mcps1.2.3.1.2 "><p id="p19162119105718"><a name="p19162119105718"></a><a name="p19162119105718"></a>删除指定的一个流水线。</p>
</td>
</tr>
<tr id="row637518252564"><td class="cellrowborder" valign="top" width="32.16%" headers="mcps1.2.3.1.1 "><p id="p937572518561"><a name="p937572518561"></a><a name="p937572518561"></a><a href="查询流水线详情.md">查询流水线详情</a></p>
</td>
<td class="cellrowborder" valign="top" width="67.84%" headers="mcps1.2.3.1.2 "><p id="p1634552225713"><a name="p1634552225713"></a><a name="p1634552225713"></a>查询流水线详情，包括<span>流水线名</span>、流水线id、<span>流水线组id</span>、<span>流水线组名</span>、流水线描述、<span>流水线执行的前置操作</span>、<span>流水线的执行步骤</span>等。</p>
</td>
</tr>
<tr id="row18567102535619"><td class="cellrowborder" valign="top" width="32.16%" headers="mcps1.2.3.1.1 "><p id="p856719253562"><a name="p856719253562"></a><a name="p856719253562"></a><a href="查询流水线列表.md">查询流水线列表</a></p>
</td>
<td class="cellrowborder" valign="top" width="67.84%" headers="mcps1.2.3.1.2 "><p id="p41552026155716"><a name="p41552026155716"></a><a name="p41552026155716"></a>查询流水线列表。</p>
</td>
</tr>
<tr id="row1276318251566"><td class="cellrowborder" valign="top" width="32.16%" headers="mcps1.2.3.1.1 "><p id="p167631825115618"><a name="p167631825115618"></a><a name="p167631825115618"></a><a href="Webhook触发流水线或执行步骤.md">Webhook触发流水线或执行步骤</a></p>
</td>
<td class="cellrowborder" valign="top" width="67.84%" headers="mcps1.2.3.1.2 "><p id="p14062915711"><a name="p14062915711"></a><a name="p14062915711"></a>通过流水线或执行步骤前置操作中webhook类型的url触发流水线或stage。</p>
</td>
</tr>
<tr id="row1392882555619"><td class="cellrowborder" valign="top" width="32.16%" headers="mcps1.2.3.1.1 "><p id="p14928162555618"><a name="p14928162555618"></a><a name="p14928162555618"></a><a href="获取执行步骤的执行历史.md">获取执行步骤的执行历史</a></p>
</td>
<td class="cellrowborder" valign="top" width="67.84%" headers="mcps1.2.3.1.2 "><p id="p1165814349572"><a name="p1165814349572"></a><a name="p1165814349572"></a>获取执行步骤的执行历史。</p>
</td>
</tr>
<tr id="row2128102645614"><td class="cellrowborder" valign="top" width="32.16%" headers="mcps1.2.3.1.1 "><p id="p1612817268564"><a name="p1612817268564"></a><a name="p1612817268564"></a><a href="获取执行步骤的执行日志.md">获取执行步骤的执行日志</a></p>
</td>
<td class="cellrowborder" valign="top" width="67.84%" headers="mcps1.2.3.1.2 "><p id="p17745183817575"><a name="p17745183817575"></a><a name="p17745183817575"></a>获取执行步骤的执行日志。</p>
</td>
</tr>
<tr id="row63841426105616"><td class="cellrowborder" valign="top" width="32.16%" headers="mcps1.2.3.1.1 "><p id="p183841326165617"><a name="p183841326165617"></a><a name="p183841326165617"></a><a href="重试或回滚执行步骤.md">重试或回滚执行步骤</a></p>
</td>
<td class="cellrowborder" valign="top" width="67.84%" headers="mcps1.2.3.1.2 "><p id="p128970415576"><a name="p128970415576"></a><a name="p128970415576"></a>重试或回滚执行步骤。</p>
</td>
</tr>
<tr id="row156091826105610"><td class="cellrowborder" valign="top" width="32.16%" headers="mcps1.2.3.1.1 "><p id="p17609122655610"><a name="p17609122655610"></a><a name="p17609122655610"></a><a href="配置执行步骤的执行信息.md">配置执行步骤的执行信息</a></p>
</td>
<td class="cellrowborder" valign="top" width="67.84%" headers="mcps1.2.3.1.2 "><p id="p78615189398"><a name="p78615189398"></a><a name="p78615189398"></a>配置执行步骤执行信息，用于审核等。</p>
</td>
</tr>
</tbody>
</table>

## 软件包管理接口<a name="section11826708186"></a>

软件包管理接口，包括获取软件包列表、获取软件包版本的文件列表、下载文件的接口等。

**表 3**  软件包管理接口

<a name="table4826405189"></a>
<table><thead align="left"><tr id="row15826100131820"><th class="cellrowborder" valign="top" width="32%" id="mcps1.2.3.1.1"><p id="p782613021811"><a name="p782613021811"></a><a name="p782613021811"></a>API</p>
</th>
<th class="cellrowborder" valign="top" width="68%" id="mcps1.2.3.1.2"><p id="p12826700189"><a name="p12826700189"></a><a name="p12826700189"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row17826303182"><td class="cellrowborder" valign="top" width="32%" headers="mcps1.2.3.1.1 "><p id="p8671221151811"><a name="p8671221151811"></a><a name="p8671221151811"></a><a href="获取软件包列表.md">获取软件包列表</a></p>
</td>
<td class="cellrowborder" valign="top" width="68%" headers="mcps1.2.3.1.2 "><p id="p467113219186"><a name="p467113219186"></a><a name="p467113219186"></a>获取软件包列表。</p>
</td>
</tr>
<tr id="row379981721817"><td class="cellrowborder" valign="top" width="32%" headers="mcps1.2.3.1.1 "><p id="p18671121141819"><a name="p18671121141819"></a><a name="p18671121141819"></a><a href="获取软件包版本列表.md">获取软件包版本列表</a></p>
</td>
<td class="cellrowborder" valign="top" width="68%" headers="mcps1.2.3.1.2 "><p id="p167113215182"><a name="p167113215182"></a><a name="p167113215182"></a>获取软件包版本列表。</p>
</td>
</tr>
<tr id="row108261800180"><td class="cellrowborder" valign="top" width="32%" headers="mcps1.2.3.1.1 "><p id="p367192120185"><a name="p367192120185"></a><a name="p367192120185"></a><a href="获取软件包版本的文件列表.md">获取软件包版本的文件列表</a></p>
</td>
<td class="cellrowborder" valign="top" width="68%" headers="mcps1.2.3.1.2 "><p id="p186711121101818"><a name="p186711121101818"></a><a name="p186711121101818"></a>获取软件包版本的文件列表。</p>
</td>
</tr>
<tr id="row1182640141812"><td class="cellrowborder" valign="top" width="32%" headers="mcps1.2.3.1.1 "><p id="p126712021201812"><a name="p126712021201812"></a><a name="p126712021201812"></a><a href="下载文件.md">下载文件</a></p>
</td>
<td class="cellrowborder" valign="top" width="68%" headers="mcps1.2.3.1.2 "><p id="p167182112183"><a name="p167182112183"></a><a name="p167182112183"></a>下载文件。</p>
</td>
</tr>
</tbody>
</table>

