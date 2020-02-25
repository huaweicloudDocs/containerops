# 构建节点与私有GitLab之间的访问<a name="ops_01_0011"></a>

如果是在您的内部网络搭建的私有GitLab，希望使用ContainerOps的源码构建功能，则需要把构建节点的相关IP段放入私有GitLab服务的白名单内，允许这些节点从私有GitLab上下载源码（即构建节点与私有GitLab之间能访问）。

当前构建节点的IP为：

**表 1**  节点IP

<a name="table1092522314284"></a>
<table><thead align="left"><tr id="row1892622315285"><th class="cellrowborder" valign="top" width="48%" id="mcps1.2.3.1.1"><p id="p1292632392815"><a name="p1292632392815"></a><a name="p1292632392815"></a>区域</p>
</th>
<th class="cellrowborder" valign="top" width="52%" id="mcps1.2.3.1.2"><p id="p1692713231287"><a name="p1692713231287"></a><a name="p1692713231287"></a>IP</p>
</th>
</tr>
</thead>
<tbody><tr id="row8927723192820"><td class="cellrowborder" valign="top" width="48%" headers="mcps1.2.3.1.1 "><p id="p1692742372820"><a name="p1692742372820"></a><a name="p1692742372820"></a><span class="keyword" id="keyword3591145413384"><a name="keyword3591145413384"></a><a name="keyword3591145413384"></a>华北-北京一</span>（cn-north-1）</p>
</td>
<td class="cellrowborder" valign="top" width="52%" headers="mcps1.2.3.1.2 "><p id="p17177022142916"><a name="p17177022142916"></a><a name="p17177022142916"></a>49.4.81.2、49.4.82.69、49.4.87.86、49.4.88.200、49.4.91.147、159.138.7.49、159.138.7.136、159.138.23.249、159.138.23.237、159.138.6.168、43.254.0.4</p>
</td>
</tr>
<tr id="row1782204610331"><td class="cellrowborder" valign="top" width="48%" headers="mcps1.2.3.1.1 "><p id="p882244603311"><a name="p882244603311"></a><a name="p882244603311"></a>华北-北京四（<span>cn-north-4</span>）</p>
</td>
<td class="cellrowborder" valign="top" width="52%" headers="mcps1.2.3.1.2 "><p id="p14343161816378"><a name="p14343161816378"></a><a name="p14343161816378"></a>119.3.252.199、119.3.248.71、117.78.9.100、117.78.10.15、159.138.7.49、159.138.7.136、159.138.23.249、159.138.23.237、159.138.6.168、49.4.112.85</p>
</td>
</tr>
<tr id="row189271623142812"><td class="cellrowborder" valign="top" width="48%" headers="mcps1.2.3.1.1 "><p id="p1927142310281"><a name="p1927142310281"></a><a name="p1927142310281"></a><span>华南-广州</span>（cn-south-1）</p>
</td>
<td class="cellrowborder" valign="top" width="52%" headers="mcps1.2.3.1.2 "><p id="p176240203013"><a name="p176240203013"></a><a name="p176240203013"></a>139.159.227.14、139.9.4.251、139.9.5.46、139.159.215.77、139.9.2.39、159.138.7.49、</p>
<p id="p12666138306"><a name="p12666138306"></a><a name="p12666138306"></a>159.138.7.136、159.138.23.249、159.138.23.237、159.138.6.168、139.159.208.37</p>
</td>
</tr>
<tr id="row392732342811"><td class="cellrowborder" valign="top" width="48%" headers="mcps1.2.3.1.1 "><p id="p358291513016"><a name="p358291513016"></a><a name="p358291513016"></a><span>华东-上海二</span>（cn-east-2）</p>
</td>
<td class="cellrowborder" valign="top" width="52%" headers="mcps1.2.3.1.2 "><p id="p5777041202716"><a name="p5777041202716"></a><a name="p5777041202716"></a>119.3.54.157、119.3.57.201、119.3.60.120、119.3.58.111、119.3.50.221、159.138.7.49、159.138.7.136、159.138.23.249、159.138.23.237、159.138.6.168、122.112.208.12</p>
</td>
</tr>
<tr id="row126221944163216"><td class="cellrowborder" valign="top" width="48%" headers="mcps1.2.3.1.1 "><p id="p186231944163216"><a name="p186231944163216"></a><a name="p186231944163216"></a><span>华东-上海一</span>（cn-east-3）</p>
</td>
<td class="cellrowborder" valign="top" width="52%" headers="mcps1.2.3.1.2 "><p id="p117977513374"><a name="p117977513374"></a><a name="p117977513374"></a>121.36.230.244、121.36.213.242、121.36.249.252、121.36.254.119、121.36.227.150、159.138.7.49、159.138.7.136、159.138.23.249、159.138.23.237、159.138.6.168、119.3.120.100</p>
</td>
</tr>
<tr id="row16461223113612"><td class="cellrowborder" valign="top" width="48%" headers="mcps1.2.3.1.1 "><p id="p18198835143615"><a name="p18198835143615"></a><a name="p18198835143615"></a>亚太-新加坡（ap-southeast-3）</p>
</td>
<td class="cellrowborder" valign="top" width="52%" headers="mcps1.2.3.1.2 "><p id="p19198133533611"><a name="p19198133533611"></a><a name="p19198133533611"></a>159.138.98.181、159.138.91.16、159.138.89.160、159.138.86.158、159.138.89.90、159.138.80.89</p>
</td>
</tr>
</tbody>
</table>

