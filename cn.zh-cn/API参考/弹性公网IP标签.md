# 弹性公网IP标签<a name="eip_apipermission_0005"></a>

<a name="zh-cn_topic_0201534116_table1877617451848"></a>
<table><thead align="left"><tr id="zh-cn_topic_0201534116_row12776124514415"><th class="cellrowborder" valign="top" width="33.27722772277228%" id="mcps1.1.5.1.1"><p id="zh-cn_topic_0201534116_p877604516418"><a name="zh-cn_topic_0201534116_p877604516418"></a><a name="zh-cn_topic_0201534116_p877604516418"></a>API</p>
</th>
<th class="cellrowborder" valign="top" width="15.237623762376238%" id="mcps1.1.5.1.2"><p id="zh-cn_topic_0201534116_p1177718454414"><a name="zh-cn_topic_0201534116_p1177718454414"></a><a name="zh-cn_topic_0201534116_p1177718454414"></a>API功能</p>
</th>
<th class="cellrowborder" valign="top" width="18.81188118811881%" id="mcps1.1.5.1.3"><p id="zh-cn_topic_0201534116_p20777945246"><a name="zh-cn_topic_0201534116_p20777945246"></a><a name="zh-cn_topic_0201534116_p20777945246"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="32.67326732673268%" id="mcps1.1.5.1.4"><p id="zh-cn_topic_0201534116_p0777174512419"><a name="zh-cn_topic_0201534116_p0777174512419"></a><a name="zh-cn_topic_0201534116_p0777174512419"></a>授权项作用域</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0201534116_row197771453415"><td class="cellrowborder" valign="top" width="33.27722772277228%" headers="mcps1.1.5.1.1 "><p id="zh-cn_topic_0201534116_p1994810358574"><a name="zh-cn_topic_0201534116_p1994810358574"></a><a name="zh-cn_topic_0201534116_p1994810358574"></a>POST /v2.0/{project_id}/publicips/{publicip_id}/tags</p>
</td>
<td class="cellrowborder" valign="top" width="15.237623762376238%" headers="mcps1.1.5.1.2 "><p id="zh-cn_topic_0201534116_p1177710451042"><a name="zh-cn_topic_0201534116_p1177710451042"></a><a name="zh-cn_topic_0201534116_p1177710451042"></a>创建弹性公网IP资源标签</p>
</td>
<td class="cellrowborder" valign="top" width="18.81188118811881%" headers="mcps1.1.5.1.3 "><p id="zh-cn_topic_0201534116_p877715451249"><a name="zh-cn_topic_0201534116_p877715451249"></a><a name="zh-cn_topic_0201534116_p877715451249"></a>vpc:publicipTags:create</p>
</td>
<td class="cellrowborder" valign="top" width="32.67326732673268%" headers="mcps1.1.5.1.4 "><a name="zh-cn_topic_0201534116_ul1698036164514"></a><a name="zh-cn_topic_0201534116_ul1698036164514"></a><ul id="zh-cn_topic_0201534116_ul1698036164514"><li>支持：项目（Project）</li><li>不支持：企业项目（Enterprise Project）</li></ul>
</td>
</tr>
<tr id="zh-cn_topic_0201534116_row127773451142"><td class="cellrowborder" valign="top" width="33.27722772277228%" headers="mcps1.1.5.1.1 "><p id="zh-cn_topic_0201534116_p177774455413"><a name="zh-cn_topic_0201534116_p177774455413"></a><a name="zh-cn_topic_0201534116_p177774455413"></a>GET /v2.0/{project_id}/publicips/{publicip_id}/tags</p>
</td>
<td class="cellrowborder" valign="top" width="15.237623762376238%" headers="mcps1.1.5.1.2 "><p id="zh-cn_topic_0201534116_p177771457412"><a name="zh-cn_topic_0201534116_p177771457412"></a><a name="zh-cn_topic_0201534116_p177771457412"></a>查询弹性公网IP资源标签</p>
</td>
<td class="cellrowborder" valign="top" width="18.81188118811881%" headers="mcps1.1.5.1.3 "><p id="zh-cn_topic_0201534116_p97779454415"><a name="zh-cn_topic_0201534116_p97779454415"></a><a name="zh-cn_topic_0201534116_p97779454415"></a>vpc:publicipTags:get</p>
</td>
<td class="cellrowborder" valign="top" width="32.67326732673268%" headers="mcps1.1.5.1.4 "><a name="zh-cn_topic_0201534116_ul1982018556594"></a><a name="zh-cn_topic_0201534116_ul1982018556594"></a><ul id="zh-cn_topic_0201534116_ul1982018556594"><li>支持：项目（Project）</li><li>不支持：企业项目（Enterprise Project）</li></ul>
</td>
</tr>
<tr id="zh-cn_topic_0201534116_row117775452419"><td class="cellrowborder" valign="top" width="33.27722772277228%" headers="mcps1.1.5.1.1 "><p id="zh-cn_topic_0201534116_p10777124513414"><a name="zh-cn_topic_0201534116_p10777124513414"></a><a name="zh-cn_topic_0201534116_p10777124513414"></a>DELETE /v2.0/{project_id}/publicips/{publicip_id}/tags/{key}</p>
</td>
<td class="cellrowborder" valign="top" width="15.237623762376238%" headers="mcps1.1.5.1.2 "><p id="zh-cn_topic_0201534116_p577714515414"><a name="zh-cn_topic_0201534116_p577714515414"></a><a name="zh-cn_topic_0201534116_p577714515414"></a>删除弹性公网IP资源标签</p>
</td>
<td class="cellrowborder" valign="top" width="18.81188118811881%" headers="mcps1.1.5.1.3 "><p id="zh-cn_topic_0201534116_p27775454417"><a name="zh-cn_topic_0201534116_p27775454417"></a><a name="zh-cn_topic_0201534116_p27775454417"></a>vpc:publicipTags:delete</p>
</td>
<td class="cellrowborder" valign="top" width="32.67326732673268%" headers="mcps1.1.5.1.4 "><a name="zh-cn_topic_0201534116_ul1381845613592"></a><a name="zh-cn_topic_0201534116_ul1381845613592"></a><ul id="zh-cn_topic_0201534116_ul1381845613592"><li>支持：项目（Project）</li><li>不支持：企业项目（Enterprise Project）</li></ul>
</td>
</tr>
<tr id="zh-cn_topic_0201534116_row5777114510411"><td class="cellrowborder" valign="top" width="33.27722772277228%" headers="mcps1.1.5.1.1 "><p id="zh-cn_topic_0201534116_p6777144516417"><a name="zh-cn_topic_0201534116_p6777144516417"></a><a name="zh-cn_topic_0201534116_p6777144516417"></a>POST /v2.0/{project_id}/publicips/{publicip_id}/tags/action</p>
</td>
<td class="cellrowborder" valign="top" width="15.237623762376238%" headers="mcps1.1.5.1.2 "><p id="zh-cn_topic_0201534116_p1077794511419"><a name="zh-cn_topic_0201534116_p1077794511419"></a><a name="zh-cn_topic_0201534116_p1077794511419"></a>批量创建和删除弹性公网IP资源标签</p>
</td>
<td class="cellrowborder" valign="top" width="18.81188118811881%" headers="mcps1.1.5.1.3 "><p id="zh-cn_topic_0201534116_p12618529014"><a name="zh-cn_topic_0201534116_p12618529014"></a><a name="zh-cn_topic_0201534116_p12618529014"></a>vpc:publicipTags:create</p>
<p id="zh-cn_topic_0201534116_p27771845341"><a name="zh-cn_topic_0201534116_p27771845341"></a><a name="zh-cn_topic_0201534116_p27771845341"></a>vpc:publicipTags:delete</p>
</td>
<td class="cellrowborder" valign="top" width="32.67326732673268%" headers="mcps1.1.5.1.4 "><a name="zh-cn_topic_0201534116_ul66121457145918"></a><a name="zh-cn_topic_0201534116_ul66121457145918"></a><ul id="zh-cn_topic_0201534116_ul66121457145918"><li>支持：项目（Project）</li><li>不支持：企业项目（Enterprise Project）</li></ul>
</td>
</tr>
<tr id="zh-cn_topic_0201534116_row1141921219586"><td class="cellrowborder" valign="top" width="33.27722772277228%" headers="mcps1.1.5.1.1 "><p id="zh-cn_topic_0201534116_p842291235811"><a name="zh-cn_topic_0201534116_p842291235811"></a><a name="zh-cn_topic_0201534116_p842291235811"></a>POST /v2.0/{project_id}/publicips/resource_instances/action</p>
</td>
<td class="cellrowborder" valign="top" width="15.237623762376238%" headers="mcps1.1.5.1.2 "><p id="zh-cn_topic_0201534116_p1242216120589"><a name="zh-cn_topic_0201534116_p1242216120589"></a><a name="zh-cn_topic_0201534116_p1242216120589"></a>查询弹性公网IP资源实例</p>
</td>
<td class="cellrowborder" valign="top" width="18.81188118811881%" headers="mcps1.1.5.1.3 "><p id="zh-cn_topic_0201534116_p16422151245812"><a name="zh-cn_topic_0201534116_p16422151245812"></a><a name="zh-cn_topic_0201534116_p16422151245812"></a>vpc:publicipTags:get</p>
</td>
<td class="cellrowborder" valign="top" width="32.67326732673268%" headers="mcps1.1.5.1.4 "><a name="zh-cn_topic_0201534116_ul1155955819590"></a><a name="zh-cn_topic_0201534116_ul1155955819590"></a><ul id="zh-cn_topic_0201534116_ul1155955819590"><li>支持：项目（Project）</li><li>不支持：企业项目（Enterprise Project）</li></ul>
</td>
</tr>
<tr id="zh-cn_topic_0201534116_row65981915155810"><td class="cellrowborder" valign="top" width="33.27722772277228%" headers="mcps1.1.5.1.1 "><p id="zh-cn_topic_0201534116_p197780456413"><a name="zh-cn_topic_0201534116_p197780456413"></a><a name="zh-cn_topic_0201534116_p197780456413"></a>GET /v2.0/{project_id}/publicips/tags</p>
</td>
<td class="cellrowborder" valign="top" width="15.237623762376238%" headers="mcps1.1.5.1.2 "><p id="zh-cn_topic_0201534116_p11599181585812"><a name="zh-cn_topic_0201534116_p11599181585812"></a><a name="zh-cn_topic_0201534116_p11599181585812"></a>查询弹性公网IP项目标签</p>
</td>
<td class="cellrowborder" valign="top" width="18.81188118811881%" headers="mcps1.1.5.1.3 "><p id="zh-cn_topic_0201534116_p5599171518589"><a name="zh-cn_topic_0201534116_p5599171518589"></a><a name="zh-cn_topic_0201534116_p5599171518589"></a>vpc:publicipTags:get</p>
</td>
<td class="cellrowborder" valign="top" width="32.67326732673268%" headers="mcps1.1.5.1.4 "><a name="zh-cn_topic_0201534116_ul21791902013"></a><a name="zh-cn_topic_0201534116_ul21791902013"></a><ul id="zh-cn_topic_0201534116_ul21791902013"><li>支持：项目（Project）</li><li>不支持：企业项目（Enterprise Project）</li></ul>
</td>
</tr>
</tbody>
</table>

