# 弹性公网IP<a name="eip_apipermission_0002"></a>

<a name="zh-cn_topic_0201534207_table3381441153612"></a>
<table><thead align="left"><tr id="zh-cn_topic_0201534207_row134361241153612"><th class="cellrowborder" valign="top" width="34%" id="mcps1.1.5.1.1"><p id="zh-cn_topic_0201534207_p24367414363"><a name="zh-cn_topic_0201534207_p24367414363"></a><a name="zh-cn_topic_0201534207_p24367414363"></a>API</p>
</th>
<th class="cellrowborder" valign="top" width="22%" id="mcps1.1.5.1.2"><p id="zh-cn_topic_0201534207_p423285813514"><a name="zh-cn_topic_0201534207_p423285813514"></a><a name="zh-cn_topic_0201534207_p423285813514"></a>API功能</p>
</th>
<th class="cellrowborder" valign="top" width="15%" id="mcps1.1.5.1.3"><p id="zh-cn_topic_0201534207_p2436194193616"><a name="zh-cn_topic_0201534207_p2436194193616"></a><a name="zh-cn_topic_0201534207_p2436194193616"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="28.999999999999996%" id="mcps1.1.5.1.4"><p id="zh-cn_topic_0201534207_p1366363695811"><a name="zh-cn_topic_0201534207_p1366363695811"></a><a name="zh-cn_topic_0201534207_p1366363695811"></a>授权项作用域</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0201534207_row943674133617"><td class="cellrowborder" valign="top" width="34%" headers="mcps1.1.5.1.1 "><p id="zh-cn_topic_0201534207_p144365416368"><a name="zh-cn_topic_0201534207_p144365416368"></a><a name="zh-cn_topic_0201534207_p144365416368"></a>POST /v1/{project_id}/publicips</p>
</td>
<td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.2 "><p id="zh-cn_topic_0201534207_p13232958145117"><a name="zh-cn_topic_0201534207_p13232958145117"></a><a name="zh-cn_topic_0201534207_p13232958145117"></a>申请弹性公网IP</p>
</td>
<td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.3 "><p id="zh-cn_topic_0201534207_p17904175011365"><a name="zh-cn_topic_0201534207_p17904175011365"></a><a name="zh-cn_topic_0201534207_p17904175011365"></a>vpc:publicIps:create</p>
</td>
<td class="cellrowborder" valign="top" width="28.999999999999996%" headers="mcps1.1.5.1.4 "><p id="zh-cn_topic_0201534207_p107185052510"><a name="zh-cn_topic_0201534207_p107185052510"></a><a name="zh-cn_topic_0201534207_p107185052510"></a>支持：项目（Project）、企业项目（Enterprise Project）</p>
</td>
</tr>
<tr id="zh-cn_topic_0201534207_row343704173619"><td class="cellrowborder" valign="top" width="34%" headers="mcps1.1.5.1.1 "><p id="zh-cn_topic_0201534207_p174371341133618"><a name="zh-cn_topic_0201534207_p174371341133618"></a><a name="zh-cn_topic_0201534207_p174371341133618"></a>GET /v1/{project_id}/publicips/{publicip_id}</p>
</td>
<td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.2 "><p id="zh-cn_topic_0201534207_p1623218589512"><a name="zh-cn_topic_0201534207_p1623218589512"></a><a name="zh-cn_topic_0201534207_p1623218589512"></a>查询弹性公网IP</p>
</td>
<td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.3 "><p id="zh-cn_topic_0201534207_p8360152113611"><a name="zh-cn_topic_0201534207_p8360152113611"></a><a name="zh-cn_topic_0201534207_p8360152113611"></a>vpc:publicIps:get</p>
</td>
<td class="cellrowborder" valign="top" width="28.999999999999996%" headers="mcps1.1.5.1.4 "><p id="zh-cn_topic_0201534207_p117181501259"><a name="zh-cn_topic_0201534207_p117181501259"></a><a name="zh-cn_topic_0201534207_p117181501259"></a>支持：项目（Project）、企业项目（Enterprise Project）</p>
</td>
</tr>
<tr id="zh-cn_topic_0201534207_row34371241143616"><td class="cellrowborder" valign="top" width="34%" headers="mcps1.1.5.1.1 "><p id="zh-cn_topic_0201534207_p16437174193619"><a name="zh-cn_topic_0201534207_p16437174193619"></a><a name="zh-cn_topic_0201534207_p16437174193619"></a>GET /v1/{project_id}/publicips</p>
</td>
<td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.2 "><p id="zh-cn_topic_0201534207_p182321558155116"><a name="zh-cn_topic_0201534207_p182321558155116"></a><a name="zh-cn_topic_0201534207_p182321558155116"></a>查询弹性公网IP列表</p>
</td>
<td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.3 "><p id="zh-cn_topic_0201534207_p35961753143612"><a name="zh-cn_topic_0201534207_p35961753143612"></a><a name="zh-cn_topic_0201534207_p35961753143612"></a>vpc:publicIps:list</p>
</td>
<td class="cellrowborder" valign="top" width="28.999999999999996%" headers="mcps1.1.5.1.4 "><p id="zh-cn_topic_0201534207_p1719903254"><a name="zh-cn_topic_0201534207_p1719903254"></a><a name="zh-cn_topic_0201534207_p1719903254"></a>支持：项目（Project）、企业项目（Enterprise Project）</p>
</td>
</tr>
<tr id="zh-cn_topic_0201534207_row443713412363"><td class="cellrowborder" valign="top" width="34%" headers="mcps1.1.5.1.1 "><p id="zh-cn_topic_0201534207_p4437194193614"><a name="zh-cn_topic_0201534207_p4437194193614"></a><a name="zh-cn_topic_0201534207_p4437194193614"></a>PUT /v1/{project_id}/publicips/{publicip_id}</p>
</td>
<td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.2 "><p id="zh-cn_topic_0201534207_p623295805113"><a name="zh-cn_topic_0201534207_p623295805113"></a><a name="zh-cn_topic_0201534207_p623295805113"></a>更新弹性公网IP</p>
</td>
<td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.3 "><p id="zh-cn_topic_0201534207_p1060705413366"><a name="zh-cn_topic_0201534207_p1060705413366"></a><a name="zh-cn_topic_0201534207_p1060705413366"></a>vpc:publicIps:update</p>
</td>
<td class="cellrowborder" valign="top" width="28.999999999999996%" headers="mcps1.1.5.1.4 "><p id="zh-cn_topic_0201534207_p4719701259"><a name="zh-cn_topic_0201534207_p4719701259"></a><a name="zh-cn_topic_0201534207_p4719701259"></a>支持：项目（Project）、企业项目（Enterprise Project）</p>
</td>
</tr>
<tr id="zh-cn_topic_0201534207_row10437144143617"><td class="cellrowborder" valign="top" width="34%" headers="mcps1.1.5.1.1 "><p id="zh-cn_topic_0201534207_p2437114115362"><a name="zh-cn_topic_0201534207_p2437114115362"></a><a name="zh-cn_topic_0201534207_p2437114115362"></a>DELETE /v1/{project_id}/publicips/{publicip_id}</p>
</td>
<td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.2 "><p id="zh-cn_topic_0201534207_p923213587517"><a name="zh-cn_topic_0201534207_p923213587517"></a><a name="zh-cn_topic_0201534207_p923213587517"></a>删除弹性公网IP</p>
</td>
<td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.3 "><p id="zh-cn_topic_0201534207_p986195516362"><a name="zh-cn_topic_0201534207_p986195516362"></a><a name="zh-cn_topic_0201534207_p986195516362"></a>vpc:publicIps:delete</p>
</td>
<td class="cellrowborder" valign="top" width="28.999999999999996%" headers="mcps1.1.5.1.4 "><p id="zh-cn_topic_0201534207_p324462512713"><a name="zh-cn_topic_0201534207_p324462512713"></a><a name="zh-cn_topic_0201534207_p324462512713"></a>支持：项目（Project）、企业项目（Enterprise Project）</p>
</td>
</tr>
<tr id="zh-cn_topic_0201534207_row06971339262"><td class="cellrowborder" valign="top" width="34%" headers="mcps1.1.5.1.1 "><p id="zh-cn_topic_0201534207_p17435812172618"><a name="zh-cn_topic_0201534207_p17435812172618"></a><a name="zh-cn_topic_0201534207_p17435812172618"></a>POST /v2.0/{project_id}/publicips</p>
</td>
<td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.2 "><p id="zh-cn_topic_0201534207_p643581217266"><a name="zh-cn_topic_0201534207_p643581217266"></a><a name="zh-cn_topic_0201534207_p643581217266"></a>申请包周期弹性公网IP</p>
</td>
<td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.3 "><p id="zh-cn_topic_0201534207_p343511262614"><a name="zh-cn_topic_0201534207_p343511262614"></a><a name="zh-cn_topic_0201534207_p343511262614"></a>vpc:publicIps:create</p>
</td>
<td class="cellrowborder" valign="top" width="28.999999999999996%" headers="mcps1.1.5.1.4 "><p id="zh-cn_topic_0201534207_p5485132562616"><a name="zh-cn_topic_0201534207_p5485132562616"></a><a name="zh-cn_topic_0201534207_p5485132562616"></a>支持：项目（Project）、企业项目（Enterprise Project）</p>
</td>
</tr>
</tbody>
</table>

