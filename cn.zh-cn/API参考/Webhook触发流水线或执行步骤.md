# Webhook触发流水线或执行步骤<a name="ops_02_0040"></a>

## 功能介绍<a name="section163491716123910"></a>

通过流水线或执行步骤前置操作中webhook类型的url触发流水线或stage。

## URI<a name="section16349101618390"></a>

POST /v2/manage/webhooks/\{webhook\_id\}?\{param1\}=\{paramvalue1\}&\{params2\}=\{paramvalue2\}…

POST /v3/manage/webhooks/\{webhook\_id\}?\{param1\}=\{paramvalue1\}&\{params2\}=\{paramvalue2\}…

参数说明请参见[表1](#table33491916143913)。

**表 1**  参数说明

<a name="table33491916143913"></a>
<table><thead align="left"><tr id="row17411918103917"><th class="cellrowborder" valign="top" width="18.44815518448155%" id="mcps1.2.5.1.1"><p id="p33201813917"><a name="p33201813917"></a><a name="p33201813917"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="13.0986901309869%" id="mcps1.2.5.1.2"><p id="p103261833916"><a name="p103261833916"></a><a name="p103261833916"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="14.77852214778522%" id="mcps1.2.5.1.3"><p id="p143231833919"><a name="p143231833919"></a><a name="p143231833919"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="53.67463253674634%" id="mcps1.2.5.1.4"><p id="p103221893914"><a name="p103221893914"></a><a name="p103221893914"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row7411918173919"><td class="cellrowborder" valign="top" width="18.44815518448155%" headers="mcps1.2.5.1.1 "><p id="p5418189392"><a name="p5418189392"></a><a name="p5418189392"></a>webhook_id</p>
</td>
<td class="cellrowborder" valign="top" width="13.0986901309869%" headers="mcps1.2.5.1.2 "><p id="p11418185397"><a name="p11418185397"></a><a name="p11418185397"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="14.77852214778522%" headers="mcps1.2.5.1.3 "><p id="p1841121818398"><a name="p1841121818398"></a><a name="p1841121818398"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="53.67463253674634%" headers="mcps1.2.5.1.4 "><p id="p14151817396"><a name="p14151817396"></a><a name="p14151817396"></a>通过流水线详情接口的url获取。</p>
</td>
</tr>
<tr id="row3415187393"><td class="cellrowborder" valign="top" width="18.44815518448155%" headers="mcps1.2.5.1.1 "><p id="p5417185392"><a name="p5417185392"></a><a name="p5417185392"></a>param1</p>
</td>
<td class="cellrowborder" valign="top" width="13.0986901309869%" headers="mcps1.2.5.1.2 "><p id="p134212181396"><a name="p134212181396"></a><a name="p134212181396"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="14.77852214778522%" headers="mcps1.2.5.1.3 "><p id="p24171814392"><a name="p24171814392"></a><a name="p24171814392"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="53.67463253674634%" headers="mcps1.2.5.1.4 "><p id="p64291823910"><a name="p64291823910"></a><a name="p64291823910"></a>触发参数，在webhook trigger的触发参数定义。</p>
</td>
</tr>
<tr id="row19421189395"><td class="cellrowborder" valign="top" width="18.44815518448155%" headers="mcps1.2.5.1.1 "><p id="p17421418123915"><a name="p17421418123915"></a><a name="p17421418123915"></a>paramvalue1</p>
</td>
<td class="cellrowborder" valign="top" width="13.0986901309869%" headers="mcps1.2.5.1.2 "><p id="p242101883914"><a name="p242101883914"></a><a name="p242101883914"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="14.77852214778522%" headers="mcps1.2.5.1.3 "><p id="p1642161819390"><a name="p1642161819390"></a><a name="p1642161819390"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="53.67463253674634%" headers="mcps1.2.5.1.4 "><p id="p1742218153916"><a name="p1742218153916"></a><a name="p1742218153916"></a>触发参数param1对应的值。</p>
</td>
</tr>
<tr id="row1342418113910"><td class="cellrowborder" valign="top" width="18.44815518448155%" headers="mcps1.2.5.1.1 "><p id="p6421818203914"><a name="p6421818203914"></a><a name="p6421818203914"></a>…</p>
</td>
<td class="cellrowborder" valign="top" width="13.0986901309869%" headers="mcps1.2.5.1.2 "><p id="p343161810393"><a name="p343161810393"></a><a name="p343161810393"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="14.77852214778522%" headers="mcps1.2.5.1.3 "><p id="p5434185393"><a name="p5434185393"></a><a name="p5434185393"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="53.67463253674634%" headers="mcps1.2.5.1.4 "><p id="p84321863918"><a name="p84321863918"></a><a name="p84321863918"></a>-</p>
</td>
</tr>
</tbody>
</table>

## 请求消息<a name="section15365116193914"></a>

N/A

## 响应消息<a name="section3369516103914"></a>

**响应示例**

```
{}
```

## 状态码<a name="section1037041673916"></a>

状态码如[表2](#table937041613394)所示。

**表 2**  状态码

<a name="table937041613394"></a>
<table><thead align="left"><tr id="row11503184398"><th class="cellrowborder" valign="top" width="16.18%" id="mcps1.2.3.1.1"><p id="a7e51ed73a71e4dc29d0dd4aae3016632"><a name="a7e51ed73a71e4dc29d0dd4aae3016632"></a><a name="a7e51ed73a71e4dc29d0dd4aae3016632"></a>状态码</p>
</th>
<th class="cellrowborder" valign="top" width="83.82%" id="mcps1.2.3.1.2"><p id="aa802d02e21c944f1863435a0d11c7ec1"><a name="aa802d02e21c944f1863435a0d11c7ec1"></a><a name="aa802d02e21c944f1863435a0d11c7ec1"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row115071823910"><td class="cellrowborder" valign="top" width="16.18%" headers="mcps1.2.3.1.1 "><p id="p850131853916"><a name="p850131853916"></a><a name="p850131853916"></a>201</p>
</td>
<td class="cellrowborder" valign="top" width="83.82%" headers="mcps1.2.3.1.2 "><p id="p250151817393"><a name="p250151817393"></a><a name="p250151817393"></a>触发成功</p>
</td>
</tr>
<tr id="row145011181395"><td class="cellrowborder" valign="top" width="16.18%" headers="mcps1.2.3.1.1 "><p id="p1650151810394"><a name="p1650151810394"></a><a name="p1650151810394"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="83.82%" headers="mcps1.2.3.1.2 "><p id="p1750181812394"><a name="p1750181812394"></a><a name="p1750181812394"></a>错误的请求</p>
</td>
</tr>
<tr id="row4501818193910"><td class="cellrowborder" valign="top" width="16.18%" headers="mcps1.2.3.1.1 "><p id="p115011813398"><a name="p115011813398"></a><a name="p115011813398"></a>401</p>
</td>
<td class="cellrowborder" valign="top" width="83.82%" headers="mcps1.2.3.1.2 "><p id="p75041863916"><a name="p75041863916"></a><a name="p75041863916"></a>鉴权失败</p>
</td>
</tr>
<tr id="row1950418133918"><td class="cellrowborder" valign="top" width="16.18%" headers="mcps1.2.3.1.1 "><p id="p1550118103913"><a name="p1550118103913"></a><a name="p1550118103913"></a>500</p>
</td>
<td class="cellrowborder" valign="top" width="83.82%" headers="mcps1.2.3.1.2 "><p id="p1450111817392"><a name="p1450111817392"></a><a name="p1450111817392"></a>内部错误</p>
</td>
</tr>
<tr id="row152021753174613"><td class="cellrowborder" valign="top" width="16.18%" headers="mcps1.2.3.1.1 "><p id="p4202053144615"><a name="p4202053144615"></a><a name="p4202053144615"></a>404</p>
</td>
<td class="cellrowborder" valign="top" width="83.82%" headers="mcps1.2.3.1.2 "><p id="p12203653144618"><a name="p12203653144618"></a><a name="p12203653144618"></a>资源不存在</p>
</td>
</tr>
</tbody>
</table>

