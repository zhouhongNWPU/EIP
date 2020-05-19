# API概览<a name="eip_api02_0001"></a>

弹性公网IP所提供的接口分为EIP接口与OpenStack原生接口。

通过配合使用EIP接口和OpenStack原生接口，您可以完整的使用弹性公网IP的所有功能。

对于企业项目用户，只能使用EIP接口，各接口对应的权限说明请参见[权限策略和授权项](权限策略和授权项.md)。

**表 1**  接口说明

<a name="table1196910139114"></a>
<table><thead align="left"><tr id="row199692013411"><th class="cellrowborder" valign="top" width="22.072207220722074%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0121588224_p487811268290"><a name="zh-cn_topic_0121588224_p487811268290"></a><a name="zh-cn_topic_0121588224_p487811268290"></a><strong id="zh-cn_topic_0121588224_b1251874443714"><a name="zh-cn_topic_0121588224_b1251874443714"></a><a name="zh-cn_topic_0121588224_b1251874443714"></a>类型</strong></p>
</th>
<th class="cellrowborder" valign="top" width="22.89228922892289%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0121588224_p68781126182914"><a name="zh-cn_topic_0121588224_p68781126182914"></a><a name="zh-cn_topic_0121588224_p68781126182914"></a><strong id="zh-cn_topic_0121588224_b125201844173712"><a name="zh-cn_topic_0121588224_b125201844173712"></a><a name="zh-cn_topic_0121588224_b125201844173712"></a>子类型</strong></p>
</th>
<th class="cellrowborder" valign="top" width="55.03550355035504%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0121588224_p158781726112914"><a name="zh-cn_topic_0121588224_p158781726112914"></a><a name="zh-cn_topic_0121588224_p158781726112914"></a><strong id="zh-cn_topic_0121588224_b15203449370"><a name="zh-cn_topic_0121588224_b15203449370"></a><a name="zh-cn_topic_0121588224_b15203449370"></a>说明</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row189701131512"><td class="cellrowborder" valign="top" width="22.072207220722074%" headers="mcps1.2.4.1.1 "><p id="p14725635135317"><a name="p14725635135317"></a><a name="p14725635135317"></a>EIP接口</p>
</td>
<td class="cellrowborder" valign="top" width="22.89228922892289%" headers="mcps1.2.4.1.2 "><p id="p156231184496"><a name="p156231184496"></a><a name="p156231184496"></a>弹性公网IP</p>
</td>
<td class="cellrowborder" valign="top" width="55.03550355035504%" headers="mcps1.2.4.1.3 "><p id="p18104638134916"><a name="p18104638134916"></a><a name="p18104638134916"></a>弹性公网IP的申请、查询、更新、删除等接口。</p>
</td>
</tr>
<tr id="row2615643516"><td class="cellrowborder" valign="top" width="22.072207220722074%" headers="mcps1.2.4.1.1 "><p id="p12904162035316"><a name="p12904162035316"></a><a name="p12904162035316"></a>EIP接口</p>
</td>
<td class="cellrowborder" valign="top" width="22.89228922892289%" headers="mcps1.2.4.1.2 "><p id="p11657401016"><a name="p11657401016"></a><a name="p11657401016"></a>带宽</p>
</td>
<td class="cellrowborder" valign="top" width="55.03550355035504%" headers="mcps1.2.4.1.3 "><p id="p96141701010"><a name="p96141701010"></a><a name="p96141701010"></a>带宽的查询、更新等接口。</p>
</td>
</tr>
<tr id="row1335106103515"><td class="cellrowborder" valign="top" width="22.072207220722074%" headers="mcps1.2.4.1.1 "><p id="p12904162075319"><a name="p12904162075319"></a><a name="p12904162075319"></a>EIP接口</p>
</td>
<td class="cellrowborder" valign="top" width="22.89228922892289%" headers="mcps1.2.4.1.2 "><p id="p1109722204210"><a name="p1109722204210"></a><a name="p1109722204210"></a>带宽（V2.0）</p>
</td>
<td class="cellrowborder" valign="top" width="55.03550355035504%" headers="mcps1.2.4.1.3 "><a name="ul74921813024"></a><a name="ul74921813024"></a><ul id="ul74921813024"><li>共享带宽的创建、删除等接口。</li><li>共享带宽插入/移出弹性公网IP操作。</li></ul>
</td>
</tr>
<tr id="row36512914311"><td class="cellrowborder" valign="top" width="22.072207220722074%" headers="mcps1.2.4.1.1 "><p id="p199041120105315"><a name="p199041120105315"></a><a name="p199041120105315"></a>EIP接口</p>
</td>
<td class="cellrowborder" valign="top" width="22.89228922892289%" headers="mcps1.2.4.1.2 "><p id="p7106132215425"><a name="p7106132215425"></a><a name="p7106132215425"></a>配额</p>
</td>
<td class="cellrowborder" valign="top" width="55.03550355035504%" headers="mcps1.2.4.1.3 "><p id="p1481210321626"><a name="p1481210321626"></a><a name="p1481210321626"></a>配额查询接口。</p>
</td>
</tr>
<tr id="row166172060357"><td class="cellrowborder" valign="top" width="22.072207220722074%" headers="mcps1.2.4.1.1 "><p id="p1941615657"><a name="p1941615657"></a><a name="p1941615657"></a>EIP接口</p>
</td>
<td class="cellrowborder" valign="top" width="22.89228922892289%" headers="mcps1.2.4.1.2 "><p id="p11888313467"><a name="p11888313467"></a><a name="p11888313467"></a>弹性IP资源标签管理</p>
</td>
<td class="cellrowborder" valign="top" width="55.03550355035504%" headers="mcps1.2.4.1.3 "><p id="p389411591368"><a name="p389411591368"></a><a name="p389411591368"></a>弹性公网IP标签的创建、查询、删除等接口。</p>
<p id="p10341154735217"><a name="p10341154735217"></a><a name="p10341154735217"></a>该类型接口目前仅在“华北-北京四”、“华东-上海一”、“华东-上海二”、“西南-贵阳一”区域开放。</p>
</td>
</tr>
<tr id="row1582113610354"><td class="cellrowborder" valign="top" width="22.072207220722074%" headers="mcps1.2.4.1.1 "><p id="p207591550183610"><a name="p207591550183610"></a><a name="p207591550183610"></a>OpenStack Neutron接口</p>
</td>
<td class="cellrowborder" valign="top" width="22.89228922892289%" headers="mcps1.2.4.1.2 "><p id="p1480933469"><a name="p1480933469"></a><a name="p1480933469"></a>浮动IP</p>
</td>
<td class="cellrowborder" valign="top" width="55.03550355035504%" headers="mcps1.2.4.1.3 "><p id="p8573612133411"><a name="p8573612133411"></a><a name="p8573612133411"></a>浮动IP的查询、创建、更新、删除等接口。</p>
</td>
</tr>
</tbody>
</table>

