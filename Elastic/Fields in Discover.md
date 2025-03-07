# Fields in Discover 

***Data streams or indices.***

`.alerts-security.alerts-default,apm-*-transaction*,auditbeat-*,endgame-*,filebeat-*,logs-*,packetbeat-*,traces-apm*,winlogbeat-*,-*elastic-cloud-logs-*`

## Unique Fields with Definitions

1. **`agent.build.original`**: The original build information of the agent.
2. **`agent.ephemeral_id`**: A temporary identifier for the agent.
3. **`agent.id`**: Unique identifier for the agent.
4. **`agent.name`**: Name of the agent.
5. **`agent.name.text`**: Text representation of the agent's name.
6. **`agent.type`**: Type of the agent (e.g., filebeat, packetbeat).
7. **`agent.version`**: Version of the agent.
8. **`client.address`**: Address of the client.
9. **`client.as.number`**: Autonomous System (AS) number of the client.
10. **`client.as.organization.name`**: Name of the organization associated with the client's AS.
11. **`client.as.organization.name.text`**: Text representation of the client's AS organization name.
12. **`client.bytes`**: Number of bytes sent by the client.
13. **`client.domain`**: Domain of the client.
14. **`client.geo.city_name`**: City name of the client's location.
15. **`client.geo.continent_code`**: Continent code of the client's location.
16. **`client.geo.continent_name`**: Continent name of the client's location.
17. **`client.geo.country_iso_code`**: ISO code of the client's country.
18. **`client.geo.country_name`**: Name of the client's country.
19. **`client.geo.location`**: Geographic location of the client.
20. **`client.geo.name`**: Name of the client's geographic location.
21. **`client.geo.postal_code`**: Postal code of the client's location.
22. **`client.geo.region_iso_code`**: ISO code of the client's region.
23. **`client.geo.region_name`**: Name of the client's region.
24. **`client.geo.timezone`**: Time zone of the client's location.
25. **`client.ip`**: IP address of the client.
26. **`client.mac`**: MAC address of the client.
27. **`client.nat.ip`**: NAT IP address of the client.
28. **`client.nat.port`**: NAT port of the client.
29. **`client.packets`**: Number of packets sent by the client.
30. **`client.port`**: Port used by the client.
31. **`client.registered_domain`**: Registered domain of the client.
32. **`client.subdomain`**: Subdomain of the client.
33. **`client.top_level_domain`**: Top-level domain of the client.
34. **`client.user.domain`**: Domain of the client user.
35. **`client.user.email`**: Email address of the client user.
36. **`client.user.full_name`**: Full name of the client user.
37. **`client.user.full_name.text`**: Text representation of the client user's full name.
38. **`client.user.group.domain`**: Domain of the client user's group.
39. **`client.user.group.id`**: ID of the client user's group.
40. **`client.user.group.name`**: Name of the client user's group.
41. **`client.user.hash`**: Hash of the client user's credentials.
42. **`client.user.id`**: ID of the client user.
43. **`client.user.name`**: Name of the client user.
44. **`client.user.name.text`**: Text representation of the client user's name.
45. **`client.user.roles`**: Roles of the client user.
46. **`cloud.account.id`**: ID of the cloud account.
47. **`cloud.account.name`**: Name of the cloud account.
48. **`cloud.availability_zone`**: Availability zone of the cloud instance.
49. **`cloud.image.id`**: ID of the cloud image.
50. **`cloud.instance.id`**: ID of the cloud instance.
51. **`cloud.instance.name`**: Name of the cloud instance.
52. **`cloud.instance.name.text`**: Text representation of the cloud instance name.
53. **`cloud.machine.type`**: Type of the cloud machine.
54. **`cloud.origin.account.id`**: ID of the original cloud account.
55. **`cloud.origin.account.name`**: Name of the original cloud account.
56. **`cloud.origin.availability_zone`**: Availability zone of the original cloud instance.
57. **`cloud.origin.instance.id`**: ID of the original cloud instance.
58. **`cloud.origin.instance.name`**: Name of the original cloud instance.
59. **`cloud.origin.machine.type`**: Type of the original cloud machine.
60. **`cloud.origin.project.id`**: ID of the original cloud project.
61. **`cloud.origin.project.name`**: Name of the original cloud project.
62. **`cloud.origin.provider`**: Provider of the original cloud service.
63. **`cloud.origin.region`**: Region of the original cloud service.
64. **`cloud.origin.service.name`**: Name of the original cloud service.
65. **`cloud.project.id`**: ID of the cloud project.
66. **`cloud.project.name`**: Name of the cloud project.
67. **`cloud.provider`**: Provider of the cloud service.
68. **`cloud.region`**: Region of the cloud service.
69. **`cloud.service.name`**: Name of the cloud service.
70. **`cloud.service.name.text`**: Text representation of the cloud service name.
71. **`cloud.target.account.id`**: ID of the target cloud account.
72. **`cloud.target.account.name`**: Name of the target cloud account.
73. **`cloud.target.availability_zone`**: Availability zone of the target cloud instance.
74. **`cloud.target.instance.id`**: ID of the target cloud instance.
75. **`cloud.target.instance.name`**: Name of the target cloud instance.
76. **`cloud.target.machine.type`**: Type of the target cloud machine.
77. **`cloud.target.project.id`**: ID of the target cloud project.
78. **`cloud.target.project.name`**: Name of the target cloud project.
79. **`cloud.target.provider`**: Provider of the target cloud service.
80. **`cloud.target.region`**: Region of the target cloud service.
81. **`cloud.target.service.name`**: Name of the target cloud service.
82. **`component.binary`**: Binary name of the component.
83. **`component.dataset`**: Dataset associated with the component.
84. **`component.id`**: ID of the component.
85. **`component.old_state`**: Previous state of the component.
86. **`component.state`**: Current state of the component.
87. **`component.type`**: Type of the component.
88. **`container.cpu.usage`**: CPU usage of the container.
89. **`container.disk.read.bytes`**: Number of bytes read from disk by the container.
90. **`container.disk.write.bytes`**: Number of bytes written to disk by the container.
91. **`container.id`**: ID of the container.
92. **`container.image.hash.all`**: Hashes of the container image.
93. **`container.image.name`**: Name of the container image.
94. **`container.image.tag`**: Tag of the container image.
95. **`container.memory.usage`**: Memory usage of the container.
96. **`container.name`**: Name of the container.
97. **`container.network.egress.bytes`**: Number of bytes sent out by the container.
98. **`container.network.ingress.bytes`**: Number of bytes received by the container.
99. **`container.runtime`**: Runtime environment of the container.
100. **`container.security_context.privileged`**: Whether the container runs in privileged mode.
101. **`data_stream.dataset`**: Dataset associated with the data stream.
102. **`data_stream.namespace`**: Namespace of the data stream.
103. **`data_stream.type`**: Type of the data stream.
104. **`destination.address`**: Address of the destination.
105. **`destination.as.number`**: Autonomous System (AS) number of the destination.
106. **`destination.as.organization.name`**: Name of the organization associated with the destination's AS.
107. **`destination.as.organization.name.text`**: Text representation of the destination's AS organization name.
108. **`destination.bytes`**: Number of bytes sent to the destination.
109. **`destination.domain`**: Domain of the destination.
110. **`destination.geo.city_name`**: City name of the destination's location.
111. **`destination.geo.continent_code`**: Continent code of the destination's location.
112. **`destination.geo.continent_name`**: Continent name of the destination's location.
113. **`destination.geo.country_iso_code`**: ISO code of the destination's country.
114. **`destination.geo.country_name`**: Name of the destination's country.
115. **`destination.geo.location`**: Geographic location of the destination.
116. **`destination.geo.name`**: Name of the destination's geographic location.
117. **`destination.geo.postal_code`**: Postal code of the destination's location.
118. **`destination.geo.region_iso_code`**: ISO code of the destination's region.
119. **`destination.geo.region_name`**: Name of the destination's region.
120. **`destination.geo.timezone`**: Time zone of the destination's location.
121. **`destination.ip`**: IP address of the destination.
122. **`destination.mac`**: MAC address of the destination.
123. **`destination.nat.ip`**: NAT IP address of the destination.
124. **`destination.nat.port`**: NAT port of the destination.
125. **`destination.packets`**: Number of packets sent to the destination.
126. **`destination.port`**: Port used by the destination.
127. **`destination.registered_domain`**: Registered domain of the destination.
128. **`destination.subdomain`**: Subdomain of the destination.
129. **`destination.top_level_domain`**: Top-level domain of the destination.
130. **`destination.user.domain`**: Domain of the destination user.
131. **`destination.user.email`**: Email address of the destination user.
132. **`destination.user.full_name`**: Full name of the destination user.
133. **`destination.user.full_name.text`**: Text representation of the destination user's full name.
134. **`destination.user.group.domain`**: Domain of the destination user's group.
135. **`destination.user.group.id`**: ID of the destination user's group.
136. **`destination.user.group.name`**: Name of the destination user's group.
137. **`destination.user.hash`**: Hash of the destination user's credentials.
138. **`destination.user.id`**: ID of the destination user.
139. **`destination.user.name`**: Name of the destination user.
140. **`destination.user.name.text`**: Text representation of the destination user's name.
141. **`destination.user.roles`**: Roles of the destination user.
142. **`device.id`**: ID of the device.
143. **`device.manufacturer`**: Manufacturer of the device.
144. **`device.model.identifier`**: Identifier of the device model.
145. **`device.model.name`**: Name of the device model.
146. **`dll.code_signature.digest_algorithm`**: Algorithm used for code signing the DLL.
147. **`dll.code_signature.exists`**: Whether a code signature exists for the DLL.
148. **`dll.code_signature.signing_id`**: Signing ID of the DLL's code signature.
149. **`dll.code_signature.status`**: Status of the DLL's code signature.
150. **`dll.code_signature.subject_name`**: Subject name of the DLL's code signature.
151. **`dll.code_signature.team_id`**: Team ID of the DLL's code signature.
152. **`dll.code_signature.timestamp`**: Timestamp of the DLL's code signature.
153. **`dll.code_signature.trusted`**: Whether the DLL's code signature is trusted.
154. **`dll.code_signature.valid`**: Whether the DLL's code signature is valid.
155. **`dll.hash.md5`**: MD5 hash of the DLL.
156. **`dll.hash.sha1`**: SHA-1 hash of the DLL.
157. **`dll.hash.sha256`**: SHA-256 hash of the DLL.
158. **`dll.hash.sha384`**: SHA-384 hash of the DLL.
159. **`dll.hash.sha512`**: SHA-512 hash of the DLL.
160. **`dll.hash.ssdeep`**: ssdeep hash of the DLL.
161. **`dll.hash.tlsh`**: tlsh hash of the DLL.
162. **`dll.name`**: Name of the DLL.
163. **`dll.path`**: Path to the DLL.
164. **`dll.pe.architecture`**: Architecture of the DLL's PE file.
165. **`dll.pe.company`**: Company name in the DLL's PE file.
166. **`dll.pe.description`**: Description in the DLL's PE file.
167. **`dll.pe.file_version`**: File version in the DLL's PE file.
168. **`dll.pe.go_import_hash`**: Hash of Go imports in the DLL's PE file.
169. **`dll.pe.go_imports`**: Go imports in the DLL's PE file.
170. **`dll.pe.go_imports_names_entropy`**: Entropy of Go import names in the DLL's PE file.
171. **`dll.pe.go_imports_names_var_entropy`**: Variable entropy of Go import names in the DLL's PE file.
172. **`dll.pe.go_stripped`**: Whether Go symbols are stripped in the DLL's PE file.
173. **`dll.pe.imphash`**: Import hash of the DLL's PE file.
174. **`dll.pe.import_hash`**: Import hash of the DLL's PE file.
175. **`dll.pe.imports`**: Imports in the DLL's PE file.
176. **`dll.pe.imports_names_entropy`**: Entropy of import names in the DLL's PE file.
177. **`dll.pe.imports_names_var_entropy`**: Variable entropy of import names in the DLL's PE file.
178. **`dll.pe.original_file_name`**: Original file name in the DLL's PE file.
179. **`dll.pe.pehash`**: PE hash of the DLL.
180. **`dll.pe.product`**: Product name in the DLL's PE file.
181. **`dll.pe.sections.entropy`**: Entropy of sections in the DLL's PE file.
182. **`dll.pe.sections.name`**: Names of sections in the DLL's PE file.
183. **`dll.pe.sections.physical_size`**: Physical size of sections in the DLL's PE file.
184. **`dll.pe.sections.var_entropy`**: Variable entropy of sections in the DLL's PE file.
185. **`dll.pe.sections.virtual_size`**: Virtual size of sections in the DLL's PE file.
186. **`dns.answers.class`**: Class of DNS answers.
187. **`dns.answers.data`**: Data in DNS answers.
188. **`dns.answers.name`**: Name of DNS answers.
189. **`dns.answers.ttl`**: Time to live (TTL) of DNS answers.
190. **`dns.answers.type`**: Type of DNS answers.
191. **`dns.header_flags`**: Flags in the DNS header.
192. **`dns.id`**: ID of the DNS query.
193. **`dns.op_code`**: Operation code of the DNS query.
194. **`dns.question.class`**: Class of the DNS question.
195. **`dns.question.name`**: Name of the DNS question.
196. **`dns.question.registered_domain`**: Registered domain of the DNS question.
197. **`dns.question.subdomain`**: Subdomain of the DNS question.
198. **`dns.question.top_level_domain`**: Top-level domain of the DNS question.
199. **`dns.question.type`**: Type of the DNS question.
200. **`dns.resolved_ip`**: Resolved IP address from DNS.
201. **`dns.response_code`**: Response code of the DNS query.
202. **`dns.type`**: Type of the DNS query.
203. **`ecs.version`**: Version of the Elastic Common Schema (ECS).
204. **`elastic_agent.id`**: ID of the Elastic Agent.
205. **`elastic_agent.process`**: Process details of the Elastic Agent.
206. **`elastic_agent.snapshot`**: Snapshot information of the Elastic Agent.
207. **`elastic_agent.version`**: Version of the Elastic Agent.
208. **`email.attachments.file.extension`**: File extension of email attachments.
209. **`email.attachments.file.hash.md5`**: MD5 hash of email attachments.
210. **`email.attachments.file.hash.sha1`**: SHA-1 hash of email attachments.
211. **`email.attachments.file.hash.sha256`**: SHA-256 hash of email attachments.
212. **`email.attachments.file.hash.sha384`**: SHA-384 hash of email attachments.
213. **`email.attachments.file.hash.sha512`**: SHA-512 hash of email attachments.
214. **`email.attachments.file.hash.ssdeep`**: ssdeep hash of email attachments.
215. **`email.attachments.file.hash.tlsh`**: tlsh hash of email attachments.
216. **`email.attachments.file.mime_type`**: MIME type of email attachments.
217. **`email.attachments.file.name`**: Name of email attachments.
218. **`email.attachments.file.size`**: Size of email attachments.
219. **`email.bcc.address`**: BCC addresses in an email.
220. **`email.cc.address`**: CC addresses in an email.
221. **`email.content_type`**: Content type of the email.
222. **`email.delivery_timestamp`**: Timestamp when the email was delivered.
223. **`email.direction`**: Direction of the email (e.g., incoming, outgoing).
224. **`email.from.address`**: From address in the email.
225. **`email.local_id`**: Local ID of the email.
226. **`email.message_id`**: Message ID of the email.
227. **`email.origination_timestamp`**: Timestamp when the email was originated.
228. **`email.reply_to.address`**: Reply-to address in the email.
229. **`email.sender.address`**: Sender's address in the email.
230. **`email.subject`**: Subject of the email.
231. **`email.subject.text`**: Text representation of the email subject.
232. **`email.to.address`**: To addresses in the email.
233. **`email.x_mailer`**: X-Mailer header in the email.
234. **`error.code`**: Error code.
235. **`error.id`**: ID of the error.
236. **`error.message`**: Message describing the error.
237. **`error.stack_trace`**: Stack trace of the error.
238. **`error.stack_trace.text`**: Text representation of the error stack trace.
239. **`error.type`**: Type of the error.
240. **`event.action`**: Action captured by the event.
241. **`event.agent_id_status`**: Status of the agent ID in the event.
242. **`event.category`**: Category of the event.
243. **`event.code`**: Code associated with the event.
244. **`event.created`**: Timestamp when the event was created.
245. **`event.dataset`**: Dataset associated with the event.
246. **`event.duration`**: Duration of the event.
247. **`event.end`**: End time of the event.
248. **`event.hash`**: Hash of the event.
249. **`event.id`**: ID of the event.
250. **`event.ingested`**: Timestamp when the event was ingested.
251. **`event.kind`**: Kind of the event.
252. **`event.module`**: Module associated with the event.
253. **`event.original`**: Original event data.
254. **`event.outcome`**: Outcome of the event.
255. **`event.provider`**: Provider of the event.
256. **`event.reason`**: Reason for the event.
257. **`event.reference`**: Reference associated with the event.
258. **`event.risk_score`**: Risk score of the event.
259. **`event.risk_score_norm`**: Normalized risk score of the event.
260. **`event.sequence`**: Sequence number of the event.
261. **`event.severity`**: Severity of the event.
262. **`event.start`**: Start time of the event.
263. **`event.timezone`**: Time zone of the event.
264. **`event.type`**: Type of the event.
265. **`event.url`**: URL associated with the event.
266. **`faas.coldstart`**: Whether the function-as-a-service (FaaS) experienced a cold start.
267. **`faas.execution`**: Execution details of the FaaS.
268. **`faas.id`**: ID of the FaaS.
269. **`faas.name`**: Name of the FaaS.
270. **`faas.version`**: Version of the FaaS.
271. **`file.accessed`**: Timestamp when the file was last accessed.
272. **`file.attributes`**: Attributes of the file.
273. **`file.code_signature.digest_algorithm`**: Algorithm used for code signing the file.
274. **`file.code_signature.exists`**: Whether a code signature exists for the file.
275. **`file.code_signature.signing_id`**: Signing ID of the file's code signature.
276. **`file.code_signature.status`**: Status of the file's code signature.
277. **`file.code_signature.subject_name`**: Subject name of the file's code signature.
278. **`file.code_signature.team_id`**: Team ID of the file's code signature.
279. **`file.code_signature.timestamp`**: Timestamp of the file's code signature.
280. **`file.code_signature.trusted`**: Whether the file's code signature is trusted.
281. **`file.code_signature.valid`**: Whether the file's code signature is valid.
282. **`file.created`**: Timestamp when the file was created.
283. **`file.ctime`**: Timestamp when the file's metadata was last changed.
284. **`file.device`**: Device where the file resides.
285. **`file.directory`**: Directory of the file.
286. **`file.drive_letter`**: Drive letter of the file.
287. **`file.elf.architecture`**: Architecture of the ELF file.
288. **`file.elf.byte_order`**: Byte order of the ELF file.
289. **`file.elf.cpu_type`**: CPU type of the ELF file.
290. **`file.elf.creation_date`**: Creation date of the ELF file.
291. **`file.elf.exports`**: Exports in the ELF file.
292. **`file.elf.go_import_hash`**: Hash of Go imports in the ELF file.
293. **`file.elf.go_imports`**: Go imports in the ELF file.
294. **`file.elf.go_imports_names_entropy`**: Entropy of Go import names in the ELF file.
295. **`file.elf.go_imports_names_var_entropy`**: Variable entropy of Go import names in the ELF file.
296. **`file.elf.go_stripped`**: Whether Go symbols are stripped in the ELF file.
297. **`file.elf.header.abi_version`**: ABI version in the ELF file header.
298. **`file.elf.header.class`**: Class in the ELF file header.
299. **`file.elf.header.data`**: Data in the ELF file header.
300. **`file.elf.header.entrypoint`**: Entry point in the ELF file header.
301. **`file.elf.header.object_version`**: Object version in the ELF file header.
302. **`file.elf.header.os_abi`**: OS ABI in the ELF file header.
303. **`file.elf.header.type`**: Type in the ELF file header.
304. **`file.elf.header.version`**: Version in the ELF file header.
305. **`file.elf.import_hash`**: Import hash of the ELF file.
306. **`file.elf.imports`**: Imports in the ELF file.
307. **`file.elf.imports_names_entropy`**: Entropy of import names in the ELF file.
308. **`file.elf.imports_names_var_entropy`**: Variable entropy of import names in the ELF file.
309. **`file.elf.sections.chi2`**: Chi-squared value of sections in the ELF file.
310. **`file.elf.sections.entropy`**: Entropy of sections in the ELF file.
311. **`file.elf.sections.flags`**: Flags of sections in the ELF file.
312. **`file.elf.sections.name`**: Names of sections in the ELF file.
313. **`file.elf.sections.physical_offset`**: Physical offset of sections in the ELF file.
314. **`file.elf.sections.physical_size`**: Physical size of sections in the ELF file.
315. **`file.elf.sections.type`**: Type of sections in the ELF file.
316. **`file.elf.sections.var_entropy`**: Variable entropy of sections in the ELF file.
317. **`file.elf.sections.virtual_address`**: Virtual address of sections in the ELF file.
318. **`file.elf.sections.virtual_size`**: Virtual size of sections in the ELF file.
319. **`file.elf.segments.sections`**: Sections in ELF segments.
320. **`file.elf.segments.type`**: Type of ELF segments.
321. **`file.elf.shared_libraries`**: Shared libraries in the ELF file.
322. **`file.elf.telfhash`**: Telfhash of the ELF file.
323. **`file.extension`**: File extension.
324. **`file.fork_name`**: Name of the file fork.
325. **`file.gid`**: Group ID of the file owner.
326. **`file.group`**: Group name of the file owner.
327. **`file.hash.md5`**: MD5 hash of the file.
328. **`file.hash.sha1`**: SHA-1 hash of the file.
329. **`file.hash.sha256`**: SHA-256 hash of the file.
330. **`file.hash.sha384`**: SHA-384 hash of the file.
331. **`file.hash.sha512`**: SHA-512 hash of the file.
332. **`file.hash.ssdeep`**: ssdeep hash of the file.
333. **`file.hash.tlsh`**: tlsh hash of the file.
334. **`file.inode`**: Inode number of the file.
335. **`file.macho.go_import_hash`**: Hash of Go imports in the Mach-O file.
336. **`file.macho.go_imports`**: Go imports in the Mach-O file.
337. **`file.macho.go_imports_names_entropy`**: Entropy of Go import names in the Mach-O file.
338. **`file.macho.go_imports_names_var_entropy`**: Variable entropy of Go import names in the Mach-O file.
339. **`file.macho.go_stripped`**: Whether Go symbols are stripped in the Mach-O file.
340. **`file.macho.import_hash`**: Import hash of the Mach-O file.
341. **`file.macho.imports`**: Imports in the Mach-O file.
342. **`file.macho.imports_names_entropy`**: Entropy of import names in the Mach-O file.
343. **`file.macho.imports_names_var_entropy`**: Variable entropy of import names in the Mach-O file.
344. **`file.macho.sections.entropy`**: Entropy of sections in the Mach-O file.
345. **`file.macho.sections.name`**: Names of sections in the Mach-O file.
346. **`file.macho.sections.physical_size`**: Physical size of sections in the Mach-O file.
347. **`file.macho.sections.var_entropy`**: Variable entropy of sections in the Mach-O file.
348. **`file.macho.sections.virtual_size`**: Virtual size of sections in the Mach-O file.
349. **`file.macho.symhash`**: Symhash of the Mach-O file.
350. **`file.mime_type`**: MIME type of the file.
351. **`file.mode`**: File mode (permissions).
352. **`file.mtime`**: Timestamp when the file's contents were last modified.
353. **`file.name`**: Name of the file.
354. **`file.owner`**: Owner of the file.
355. **`file.path`**: Path to the file.
356. **`file.path.text`**: Text representation of the file path.
357. **`file.pe.architecture`**: Architecture of the PE file.
358. **`file.pe.company`**: Company name in the PE file.
359. **`file.pe.description`**: Description in the PE file.
360. **`file.pe.file_version`**: File version in the PE file.
361. **`file.pe.go_import_hash`**: Hash of Go imports in the PE file.
362. **`file.pe.go_imports`**: Go imports in the PE file.
363. **`file.pe.go_imports_names_entropy`**: Entropy of Go import names in the PE file.
364. **`file.pe.go_imports_names_var_entropy`**: Variable entropy of Go import names in the PE file.
365. **`file.pe.go_stripped`**: Whether Go symbols are stripped in the PE file.
366. **`file.pe.imphash`**: Import hash of the PE file.
367. **`file.pe.import_hash`**: Import hash of the PE file.
368. **`file.pe.imports`**: Imports in the PE file.
369. **`file.pe.imports_names_entropy`**: Entropy of import names in the PE file.
370. **`file.pe.imports_names_var_entropy`**: Variable entropy of import names in the PE file.
371. **`file.pe.original_file_name`**: Original file name in the PE file.
372. **`file.pe.pehash`**: PE hash of the file.
373. **`file.pe.product`**: Product name in the PE file.
374. **`file.pe.sections.entropy`**: Entropy of sections in the PE file.
375. **`file.pe.sections.name`**: Names of sections in the PE file.
376. **`file.pe.sections.physical_size`**: Physical size of sections in the PE file.
377. **`file.pe.sections.var_entropy`**: Variable entropy of sections in the PE file.
378. **`file.pe.sections.virtual_size`**: Virtual size of sections in the PE file.
379. **`file.size`**: Size of the file.
380. **`file.target_path`**: Target path of the file.
381. **`file.target_path.text`**: Text representation of the file target path.
382. **`file.type`**: Type of the file.
383. **`file.uid`**: User ID of the file owner.
384. **`file.x509.alternative_names`**: Alternative names in the X.509 certificate.
385. **`file.x509.issuer.common_name`**: Common name of the issuer in the X.509 certificate.
386. **`file.x509.issuer.country`**: Country of the issuer in the X.509 certificate.
387. **`file.x509.issuer.distinguished_name`**: Distinguished name of the issuer in the X.509 certificate.
388. **`file.x509.issuer.locality`**: Locality of the issuer in the X.509 certificate.
389. **`file.x509.issuer.organization`**: Organization of the issuer in the X.509 certificate.
390. **`file.x509.issuer.organizational_unit`**: Organizational unit of the issuer in the X.509 certificate.
391. **`file.x509.issuer.state_or_province`**: State or province of the issuer in the X.509 certificate.
392. **`file.x509.not_after`**: Not-after date of the X.509 certificate.
393. **`file.x509.not_before`**: Not-before date of the X.509 certificate.
394. **`file.x509.public_key_algorithm`**: Public key algorithm in the X.509 certificate.
395. **`file.x509.public_key_curve`**: Public key curve in the X.509 certificate.
396. **`file.x509.public_key_exponent`**: Public key exponent in the X.509 certificate.
397. **`file.x509.public_key_size`**: Public key size in the X.509 certificate.
398. **`file.x509.serial_number`**: Serial number of the X.509 certificate.
399. **`file.x509.signature_algorithm`**: Signature algorithm in the X.509 certificate.
400. **`file.x509.subject.common_name`**: Common name of the subject in the X.509 certificate.
401. **`file.x509.subject.country`**: Country of the subject in the X.509 certificate.
402. **`file.x509.subject.distinguished_name`**: Distinguished name of the subject in the X.509 certificate.
403. **`file.x509.subject.locality`**: Locality of the subject in the X.509 certificate.
404. **`file.x509.subject.organization`**: Organization of the subject in the X.509 certificate.
405. **`file.x509.subject.organizational_unit`**: Organizational unit of the subject in the X.509 certificate.
406. **`file.x509.subject.state_or_province`**: State or province of the subject in the X.509 certificate.
407. **`file.x509.version_number`**: Version number of the X.509 certificate.
408. **`fleet.access.apikey.id`**: ID of the API key used for Fleet access.
409. **`fleet.agent.id`**: ID of the Fleet agent.
410. **`fleet.policy.id`**: ID of the Fleet policy.
411. **`group.domain`**: Domain of the group.
412. **`group.id`**: ID of the group.
413. **`group.name`**: Name of the group.
414. **`group.name.text`**: Text representation of the group name.
415. **`host.architecture`**: Architecture of the host.
416. **`host.asset.criticality`**: Criticality of the host asset.
417. **`host.boot.id`**: ID of the host boot.
418. **`host.containerized`**: Whether the host is containerized.
419. **`host.cpu.usage`**: CPU usage of the host.
420. **`host.disk.read.bytes`**: Number of bytes read from disk by the host.
421. **`host.disk.write.bytes`**: Number of bytes written to disk by the host.  
422. **`kibana.alert.action_group`**: Group of actions associated with the alert.
423. **`kibana.alert.ancestors.depth`**: Depth of the alert's ancestors.
424. **`kibana.alert.ancestors.id`**: IDs of the alert's ancestors.
425. **`kibana.alert.ancestors.index`**: Index of the alert's ancestors.
426. **`kibana.alert.ancestors.rule`**: Rule associated with the alert's ancestors.
427. **`kibana.alert.ancestors.type`**: Type of the alert's ancestors.
428. **`kibana.alert.building_block_type`**: Type of building block used in the alert.
429. **`kibana.alert.case_ids`**: IDs of cases associated with the alert.
430. **`kibana.alert.consecutive_matches`**: Number of consecutive matches for the alert.
431. **`kibana.alert.depth`**: Depth of the alert.
432. **`kibana.alert.duration.us`**: Duration of the alert in microseconds.
433. **`kibana.alert.end`**: End time of the alert.
434. **`kibana.alert.flapping`**: Whether the alert is flapping.
435. **`kibana.alert.flapping_history`**: History of flapping for the alert.
436. **`kibana.alert.group.id`**: ID of the group associated with the alert.
437. **`kibana.alert.group.index`**: Index of the group associated with the alert.
438. **`kibana.alert.host.criticality_level`**: Criticality level of the host associated with the alert.
439. **`kibana.alert.instance.id`**: ID of the instance associated with the alert.
440. **`kibana.alert.intended_timestamp`**: Intended timestamp of the alert.
441. **`kibana.alert.last_detected`**: Timestamp when the alert was last detected.
442. **`kibana.alert.maintenance_window_ids`**: IDs of maintenance windows associated with the alert.
443. **`kibana.alert.new_terms`**: New terms associated with the alert.
444. **`kibana.alert.original_event.action`**: Action of the original event.
445. **`kibana.alert.original_event.agent_id_status`**: Agent ID status of the original event.
446. **`kibana.alert.original_event.category`**: Category of the original event.
447. **`kibana.alert.original_event.code`**: Code of the original event.
448. **`kibana.alert.original_event.created`**: Timestamp when the original event was created.
449. **`kibana.alert.original_event.dataset`**: Dataset of the original event.
450. **`kibana.alert.original_event.duration`**: Duration of the original event.
451. **`kibana.alert.original_event.end`**: End time of the original event.
452. **`kibana.alert.original_event.hash`**: Hash of the original event.
453. **`kibana.alert.original_event.id`**: ID of the original event.
454. **`kibana.alert.original_event.ingested`**: Timestamp when the original event was ingested.
455. **`kibana.alert.original_event.kind`**: Kind of the original event.
456. **`kibana.alert.original_event.module`**: Module associated with the original event.
457. **`kibana.alert.original_event.original`**: Original data of the event.
458. **`kibana.alert.original_event.outcome`**: Outcome of the original event.
459. **`kibana.alert.original_event.provider`**: Provider of the original event.
460. **`kibana.alert.original_event.reason`**: Reason for the original event.
461. **`kibana.alert.original_event.reference`**: Reference associated with the original event.
462. **`kibana.alert.original_event.risk_score`**: Risk score of the original event.
463. **`kibana.alert.original_event.risk_score_norm`**: Normalized risk score of the original event.
464. **`kibana.alert.original_event.sequence`**: Sequence number of the original event.
465. **`kibana.alert.original_event.severity`**: Severity of the original event.
466. **`kibana.alert.original_event.start`**: Start time of the original event.
467. **`kibana.alert.original_event.timezone`**: Time zone of the original event.
468. **`kibana.alert.original_event.type`**: Type of the original event.
469. **`kibana.alert.original_event.url`**: URL associated with the original event.
470. **`kibana.alert.original_time`**: Original time of the alert.
471. **`kibana.alert.previous_action_group`**: Previous action group associated with the alert.
472. **`kibana.alert.reason`**: Reason for the alert.
473. **`kibana.alert.reason.text`**: Text representation of the alert reason.
474. **`kibana.alert.risk_score`**: Risk score of the alert.
475. **`kibana.alert.rule.author`**: Author of the rule that triggered the alert.
476. **`kibana.alert.rule.building_block_type`**: Type of building block used in the rule.
477. **`kibana.alert.rule.category`**: Category of the rule.
478. **`kibana.alert.rule.consumer`**: Consumer of the rule.
479. **`kibana.alert.rule.created_at`**: Timestamp when the rule was created.
480. **`kibana.alert.rule.created_by`**: User who created the rule.
481. **`kibana.alert.rule.description`**: Description of the rule.
482. **`kibana.alert.rule.enabled`**: Whether the rule is enabled.
483. **`kibana.alert.rule.execution.timestamp`**: Timestamp of the rule execution.
484. **`kibana.alert.rule.execution.type`**: Type of rule execution.
485. **`kibana.alert.rule.execution.uuid`**: UUID of the rule execution.
486. **`kibana.alert.rule.false_positives`**: Number of false positives for the rule.
487. **`kibana.alert.rule.immutable`**: Whether the rule is immutable.
488. **`kibana.alert.rule.interval`**: Interval at which the rule is executed.
489. **`kibana.alert.rule.license`**: License associated with the rule.
490. **`kibana.alert.rule.max_signals`**: Maximum number of signals for the rule.
491. **`kibana.alert.rule.name`**: Name of the rule.
492. **`kibana.alert.rule.note`**: Note associated with the rule.
493. **`kibana.alert.rule.parameters`**: Parameters of the rule.
494. **`kibana.alert.rule.producer`**: Producer of the rule.
495. **`kibana.alert.rule.references`**: References associated with the rule.
496. **`kibana.alert.rule.revision`**: Revision number of the rule.
497. **`kibana.alert.rule.rule_id`**: ID of the rule.
498. **`kibana.alert.rule.rule_name_override`**: Override name for the rule.
499. **`kibana.alert.rule.rule_type_id`**: Type ID of the rule.
500. **`kibana.alert.rule.tags`**: Tags associated with the rule.
501. **`kibana.alert.rule.threat.framework`**: Threat framework associated with the rule.
502. **`kibana.alert.rule.threat.tactic.id`**: ID of the threat tactic.
503. **`kibana.alert.rule.threat.tactic.name`**: Name of the threat tactic.
504. **`kibana.alert.rule.threat.tactic.reference`**: Reference for the threat tactic.
505. **`kibana.alert.rule.threat.technique.id`**: ID of the threat technique.
506. **`kibana.alert.rule.threat.technique.name`**: Name of the threat technique.
507. **`kibana.alert.rule.threat.technique.reference`**: Reference for the threat technique.
508. **`kibana.alert.rule.threat.technique.subtechnique.id`**: ID of the threat subtechnique.
509. **`kibana.alert.rule.threat.technique.subtechnique.name`**: Name of the threat subtechnique.
510. **`kibana.alert.rule.threat.technique.subtechnique.reference`**: Reference for the threat subtechnique.
511. **`kibana.alert.rule.timeline_id`**: ID of the timeline associated with the rule.
512. **`kibana.alert.rule.timeline_title`**: Title of the timeline associated with the rule.
513. **`kibana.alert.rule.timestamp_override`**: Timestamp override for the rule.
514. **`kibana.alert.rule.to`**: To field of the rule.
515. **`kibana.alert.rule.type`**: Type of the rule.
516. **`kibana.alert.rule.updated_at`**: Timestamp when the rule was updated.
517. **`kibana.alert.rule.updated_by`**: User who updated the rule.
518. **`kibana.alert.rule.uuid`**: UUID of the rule.
519. **`kibana.alert.rule.version`**: Version of the rule.
520. **`kibana.alert.severity`**: Severity of the alert.
521. **`kibana.alert.severity_improving`**: Whether the alert severity is improving.
522. **`kibana.alert.start`**: Start time of the alert.
523. **`kibana.alert.status`**: Status of the alert.
524. **`kibana.alert.suppression.docs_count`**: Number of documents suppressed.
525. **`kibana.alert.suppression.end`**: End time of suppression.
526. **`kibana.alert.suppression.start`**: Start time of suppression.
527. **`kibana.alert.suppression.terms.field`**: Field used for suppression terms.
528. **`kibana.alert.suppression.terms.value`**: Value used for suppression terms.
529. **`kibana.alert.system_status`**: System status of the alert.
530. **`kibana.alert.threshold_result.cardinality.field`**: Field used for cardinality in threshold results.
531. **`kibana.alert.threshold_result.cardinality.value`**: Value used for cardinality in threshold results.
532. **`kibana.alert.threshold_result.count`**: Count of threshold results.
533. **`kibana.alert.threshold_result.from`**: From field in threshold results.
534. **`kibana.alert.threshold_result.terms.field`**: Field used for terms in threshold results.
535. **`kibana.alert.threshold_result.terms.value`**: Value used for terms in threshold results.
536. **`kibana.alert.time_range`**: Time range of the alert.
537. **`kibana.alert.url`**: URL associated with the alert.
538. **`kibana.alert.user.criticality_level`**: Criticality level of the user associated with the alert.
539. **`kibana.alert.uuid`**: UUID of the alert.
540. **`kibana.alert.workflow_assignee_ids`**: IDs of assignees in the alert workflow.
541. **`kibana.alert.workflow_reason`**: Reason for the alert workflow.
542. **`kibana.alert.workflow_status`**: Status of the alert workflow.
543. **`kibana.alert.workflow_status_updated_at`**: Timestamp when the workflow status was updated.
544. **`kibana.alert.workflow_tags`**: Tags associated with the alert workflow.
545. **`kibana.alert.workflow_user`**: User associated with the alert workflow.
546. **`kibana.space_ids`**: IDs of Kibana spaces.
547. **`kibana.version`**: Version of Kibana.
548. **`log.file.path`**: Path to the log file.
549. **`log.file.path.text`**: Text representation of the log file path.
550. **`log.level`**: Severity level of the log message.
551. **`log.logger`**: Logger name.
552. **`log.offset`**: Offset in the log file.
553. **`log.origin.file.line`**: Line number in the log file.
554. **`log.origin.file.name`**: Name of the log file.
555. **`log.origin.function`**: Function that generated the log.
556. **`log.syslog.appname`**: Application name in syslog.
557. **`log.syslog.facility.code`**: Facility code in syslog.
558. **`log.syslog.facility.name`**: Facility name in syslog.
559. **`log.syslog.hostname`**: Hostname in syslog.
560. **`log.syslog.msgid`**: Message ID in syslog.
561. **`log.syslog.priority`**: Syslog numeric priority of the event, calculated as 8 * facility + severity[1](https://www.elastic.co/guide/en/ecs/1.12/ecs-log.html)[3](https://www.elastic.co/guide/en/ecs/current/ecs-log.html).
562. **`log.syslog.procid`**: Process ID that originated the Syslog message[1](https://www.elastic.co/guide/en/ecs/1.12/ecs-log.html)[3](https://www.elastic.co/guide/en/ecs/current/ecs-log.html).
563. **`log.syslog.severity.code`**: Numeric severity of the Syslog message[1](https://www.elastic.co/guide/en/ecs/1.12/ecs-log.html)[3](https://www.elastic.co/guide/en/ecs/current/ecs-log.html).
564. **`log.syslog.severity.name`**: Text-based severity of the Syslog message[1](https://www.elastic.co/guide/en/ecs/1.12/ecs-log.html)[3](https://www.elastic.co/guide/en/ecs/current/ecs-log.html).
565. **`log.syslog.structured_data`**: Structured data expressed in RFC 5424 messages[3](https://www.elastic.co/guide/en/ecs/current/ecs-log.html).
566. **`log.syslog.version`**: Version of the Syslog protocol specification[3](https://www.elastic.co/guide/en/ecs/current/ecs-log.html).
567. **`message`**: The actual log message or event data.
568. **`monitoring.metrics.libbeat.pipeline.events.active`**: Number of active events in the Libbeat pipeline.
569. **`monitoring.metrics.libbeat.pipeline.events.published`**: Number of events published by the Libbeat pipeline.
570. **`monitoring.metrics.libbeat.pipeline.events.total`**: Total number of events in the Libbeat pipeline.
571. **`monitoring.metrics.libbeat.pipeline.queue.acked`**: Number of acknowledged events in the Libbeat queue.
572. **`monitoring.metrics.libbeat.pipeline.queue.filled.pct.events`**: Percentage of events filling the Libbeat queue.
573. **`monitoring.metrics.libbeat.pipeline.queue.max_events`**: Maximum number of events in the Libbeat queue.
574. **`network.application`**: Application involved in the network activity.
575. **`network.bytes`**: Number of bytes transferred over the network.
576. **`network.community_id`**: Community ID for network flow identification.
577. **`network.direction`**: Direction of network traffic (e.g., incoming, outgoing).
578. **`network.forwarded_ip`**: IP address forwarded by a proxy or load balancer.
579. **`network.iana_number`**: IANA-assigned number for the network protocol.
580. **`network.inner.vlan.id`**: Inner VLAN ID for network traffic.
581. **`network.inner.vlan.name`**: Inner VLAN name for network traffic.
582. **`network.name`**: Name of the network interface or connection.
583. **`network.packets`**: Number of packets transferred over the network.
584. **`network.protocol`**: Network protocol used (e.g., TCP, UDP).
585. **`network.transport`**: Transport layer protocol (e.g., TCP, UDP).
586. **`network.type`**: Type of network connection (e.g., IPv4, IPv6).
587. **`network.vlan.id`**: VLAN ID for network traffic.
588. **`network.vlan.name`**: VLAN name for network traffic.
589. **`observer.egress.interface.alias`**: Alias of the egress network interface.
590. **`observer.egress.interface.id`**: ID of the egress network interface.
591. **`observer.egress.interface.name`**: Name of the egress network interface.
592. **`observer.egress.vlan.id`**: VLAN ID of the egress network interface.
593. **`observer.egress.vlan.name`**: VLAN name of the egress network interface.
594. **`observer.egress.zone`**: Zone of the egress network interface.
595. **`observer.geo.city_name`**: City name of the observer's location.
596. **`observer.geo.continent_code`**: Continent code of the observer's location.
597. **`observer.geo.continent_name`**: Continent name of the observer's location.
598. **`observer.geo.country_iso_code`**: ISO code of the observer's country.
599. **`observer.geo.country_name`**: Name of the observer's country.
600. **`observer.geo.location`**: Geographic location of the observer.
601. **`observer.geo.name`**: Name of the observer's geographic location.
602. **`observer.geo.postal_code`**: Postal code of the observer's location.
603. **`observer.geo.region_iso_code`**: ISO code of the observer's region.
604. **`observer.geo.region_name`**: Name of the observer's region.
605. **`observer.geo.timezone`**: Time zone of the observer's location.
606. **`observer.hostname`**: Hostname of the observer.
607. **`observer.ingress.interface.alias`**: Alias of the ingress network interface.
608. **`observer.ingress.interface.id`**: ID of the ingress network interface.
609. **`observer.ingress.interface.name`**: Name of the ingress network interface.
610. **`observer.ingress.vlan.id`**: VLAN ID of the ingress network interface.
611. **`observer.ingress.vlan.name`**: VLAN name of the ingress network interface.
612. **`observer.ingress.zone`**: Zone of the ingress network interface.
613. **`observer.ip`**: IP address of the observer.
614. **`observer.mac`**: MAC address of the observer.
615. **`observer.name`**: Name of the observer.
616. **`observer.os.family`**: Family of the observer's operating system.
617. **`observer.os.full`**: Full name of the observer's operating system.
618. **`observer.os.full.text`**: Text representation of the observer's OS full name.
619. **`observer.os.kernel`**: Kernel version of the observer's operating system.
620. **`observer.os.name`**: Name of the observer's operating system.
621. **`observer.os.name.text`**: Text representation of the observer's OS name.
622. **`observer.os.platform`**: Platform of the observer's operating system.
623. **`observer.os.type`**: Type of the observer's operating system.
624. **`observer.os.version`**: Version of the observer's operating system.
625. **`observer.product`**: Product name of the observer.
626. **`observer.serial_number`**: Serial number of the observer.
627. **`observer.type`**: Type of the observer.
628. **`observer.vendor`**: Vendor of the observer.
629. **`observer.version`**: Version of the observer.
630. **`orchestrator.api_version`**: API version of the orchestrator.
631. **`orchestrator.cluster.id`**: ID of the orchestrator cluster.
632. **`orchestrator.cluster.name`**: Name of the orchestrator cluster.
633. **`orchestrator.cluster.url`**: URL of the orchestrator cluster.
634. **`orchestrator.cluster.version`**: Version of the orchestrator cluster.
635. **`orchestrator.namespace`**: Namespace of the orchestrator.
636. **`orchestrator.organization`**: Organization of the orchestrator.
637. **`orchestrator.resource.annotation`**: Annotations of the orchestrator resource.
638. **`orchestrator.resource.id`**: ID of the orchestrator resource.
639. **`orchestrator.resource.ip`**: IP address of the orchestrator resource.
640. **`orchestrator.resource.label`**: Labels of the orchestrator resource.
641. **`orchestrator.resource.name`**: Name of the orchestrator resource.
642. **`orchestrator.resource.parent.type`**: Type of the parent resource.
643. **`orchestrator.resource.type`**: Type of the orchestrator resource.
644. **`orchestrator.type`**: Type of the orchestrator.
645. **`organization.id`**: ID of the organization.
646. **`organization.name`**: Name of the organization.
647. **`organization.name.text`**: Text representation of the organization name.
648. **`package.architecture`**: Architecture of the software package.
649. **`package.build_version`**: Build version of the software package.
650. **`package.checksum`**: Checksum of the software package.
651. **`package.description`**: Description of the software package.
652. **`package.installed`**: Whether the package is installed.
653. **`package.install_scope`**: Scope of the package installation.
654. **`package.license`**: License of the software package.
655. **`package.name`**: Name of the software package.
656. **`package.path`**: Path to the software package.
657. **`package.reference`**: Reference to the software package.
658. **`package.size`**: Size of the software package.
659. **`package.type`**: Type of the software package.
660. **`package.version`**: Version of the software package.
661. **`policy_id`**: ID of the policy.
662. **`process.args`**: Arguments passed to the process.
663. **`process.args_count`**: Number of arguments passed to the process.
664. **`process.code_signature.digest_algorithm`**: Algorithm used for code signing the process.
665. **`process.code_signature.exists`**: Whether a code signature exists for the process.
666. **`process.code_signature.signing_id`**: Signing ID of the process's code signature.
667. **`process.code_signature.status`**: Status of the process's code signature.
668. **`process.code_signature.subject_name`**: Subject name of the process's code signature.
669. **`process.code_signature.team_id`**: Team ID of the process's code signature.
670. **`process.code_signature.timestamp`**: Timestamp of the process's code signature.
671. **`process.code_signature.trusted`**: Whether the process's code signature is trusted.
672. **`process.code_signature.valid`**: Whether the process's code signature is valid.
673. **`process.command_line`**: Command line used to start the process.
674. **`process.command_line.text`**: Text representation of the process command line.
675. **`process.elf.architecture`**: Architecture of the ELF file associated with the process.
676. **`process.elf.byte_order`**: Byte order of the ELF file associated with the process.
677. **`process.elf.cpu_type`**: CPU type of the ELF file associated with the process.
678. **`process.elf.creation_date`**: Creation date of the ELF file associated with the process.
679. **`process.elf.exports`**: Exports in the ELF file associated with the process.
680. **`process.elf.go_import_hash`**: Hash of Go imports in the ELF file associated with the process.
681. **`process.elf.go_imports`**: Go imports in the ELF file associated with the process.
682. **`process.elf.go_imports_names_entropy`**: Entropy of Go import names in the ELF file associated with the process.
683. **`process.elf.go_imports_names_var_entropy`**: Variable entropy of Go import names in the ELF file associated with the process.
684. **`process.elf.go_stripped`**: Whether Go symbols are stripped in the ELF file associated with the process.
685. **`process.elf.header.abi_version`**: ABI version in the ELF file header associated with the process.
686. **`process.elf.header.class`**: Class in the ELF file header associated with the process.
687. **`process.elf.header.data`**: Data in the ELF file header associated with the process.
688. **`process.elf.header.entrypoint`**: Entry point in the ELF file header associated with the process.
689. **`process.elf.header.object_version`**: Object version in the ELF file header associated with the process.
690. **`process.elf.header.os_abi`**: OS ABI in the ELF file header associated with the process.
691. **`process.elf.header.type`**: Type in the ELF file header associated with the process.
692. **`process.elf.header.version`**: Version in the ELF file header associated with the process.
693. **`process.elf.import_hash`**: Import hash of the ELF file associated with the process.
694. **`process.elf.imports`**: Imports in the ELF file associated with the process.
695. **`process.elf.imports_names_entropy`**: Entropy of import names in the ELF file associated with the process.
696. **`process.elf.imports_names_var_entropy`**: Variable entropy of import names in the ELF file associated with the process.
697. **`process.elf.sections.chi2`**: Chi-squared value of sections in the ELF file associated with the process.
698. **`process.elf.sections.entropy`**: Entropy of sections in the ELF file associated with the process.
699. **`process.elf.sections.flags`**: Flags of sections in the ELF file associated with the process.
700. **`process.elf.sections.name`**: Names of sections in the ELF file associated with the process.
701. **`process.elf.sections.physical_offset`**: Physical offset of sections in the ELF file associated with the process.
702. **`process.elf.sections.physical_size`**: Physical size of sections in the ELF file associated with the process.
703. **`process.elf.sections.type`**: Type of sections in the ELF file associated with the process.
704. **`process.elf.sections.var_entropy`**: Variable entropy of sections in the ELF file associated with the process.
705. **`process.elf.sections.virtual_address`**: Virtual address of sections in the ELF file associated with the process.
706. **`process.elf.sections.virtual_size`**: Virtual size of sections in the ELF file associated with the process.
707. **`process.elf.segments.sections`**: Sections in ELF segments associated with the process.
708. **`process.elf.segments.type`**: Type of ELF segments associated with the process.
709. **`process.elf.shared_libraries`**: Shared libraries in the ELF file associated with the process.
710. **`process.elf.telfhash`**: Telfhash of the ELF file associated with the process.
711. **`process.end`**: Timestamp when the process ended.
712. **`process.entity_id`**: Entity ID of the process.
713. **`process.entry_leader.args`**: Arguments of the entry leader process.
714. **`process.entry_leader.args_count`**: Number of arguments of the entry leader process.
715. **`process.entry_leader.attested_groups.name`**: Attested group names of the entry leader process.
716. **`process.entry_leader.attested_user.id`**: ID of the attested user of the entry leader process.
717. **`process.entry_leader.attested_user.name`**: Name of the attested user of the entry leader process.
718. **`process.entry_leader.attested_user.name.text`**: Text representation of the attested user name of the entry leader process.
719. **`process.entry_leader.command_line`**: Command line of the entry leader process.
720. **`process.entry_leader.command_line.text`**: Text representation of the command line of the entry leader process.
721. **`process.entry_leader.entity_id`**: Entity ID of the entry leader process.
722. **`process.entry_leader.entry_meta.source.ip`**: Source IP of the entry leader process metadata.
723. **`process.entry_leader.entry_meta.type`**: Type of the entry leader process metadata.
724. **`process.entry_leader.executable`**: Executable of the entry leader process.
725. **`process.entry_leader.executable.text`**: Text representation of the executable of the entry leader process.
726. **`process.entry_leader.group.id`**: ID of the group of the entry leader process.
727. **`process.entry_leader.group.name`**: Name of the group of the entry leader process.
728. **`process.entry_leader.interactive`**: Whether the entry leader process is interactive.
729. **`process.entry_leader.name`**: Name of the entry leader process.
730. **`process.entry_leader.name.text`**: Text representation of the name of the entry leader process.
731. **`process.entry_leader.parent.entity_id`**: Entity ID of the parent process of the entry leader.
732. **`process.entry_leader.parent.pid`**: PID of the parent process of the entry leader.
733. **`process.entry_leader.parent.session_leader.entity_id`**: Entity ID of the session leader parent process of the entry leader.
734. **`process.entry_leader.parent.session_leader.pid`**: PID of the session leader parent process of the entry leader.
735. **`process.entry_leader.parent.session_leader.start`**: Start time of the session leader parent process of the entry leader.
736. **`process.entry_leader.parent.session_leader.vpid`**: Virtual PID of the session leader parent process of the entry leader.
737. **`process.entry_leader.parent.start`**: Start time of the parent process of the entry leader.
738. **`process.entry_leader.parent.vpid`**: Virtual PID of the parent process of the entry leader.
739. **`process.entry_leader.pid`**: PID of the entry leader process.
740. **`process.entry_leader.real_group.id`**: ID of the real group of the entry leader process.
741. **`process.entry_leader.real_group.name`**: Name of the real group of the entry leader process.
742. **`process.entry_leader.real_user.id`**: ID of the real user of the entry leader process.
743. **`process.entry_leader.real_user.name`**: Name of the real user of the entry leader process.
744. **`process.entry_leader.real_user.name.text`**: Text representation of the real user name of the entry leader process.
745. **`process.entry_leader.saved_group.id`**: ID of the saved group of the entry leader process.
746. **`process.entry_leader.saved_group.name`**: Name of the saved group of the entry leader process.
747. **`process.entry_leader.saved_user.id`**: ID of the saved user of the entry leader process.
748. **`process.entry_leader.saved_user.name`**: Name of the saved user of the entry leader process.
749. **`process.entry_leader.saved_user.name.text`**: Text representation of the saved user name of the entry leader process.
750. **`process.entry_leader.start`**: Start time of the entry leader process.
751. **`process.entry_leader.supplemental_groups.id`**: IDs of supplemental groups of the entry leader process.
752. **`process.entry_leader.supplemental_groups.name`**: Names of supplemental groups of the entry leader process.
753. **`process.entry_leader.tty.char_device.major`**: Major number of the character device associated with the entry leader process's TTY.
754. **`process.entry_leader.tty.char_device.minor`**: Minor number of the character device associated with the entry leader process's TTY.
755. **`process.entry_leader.user.id`**: ID of the user of the entry leader process.
756. **`process.entry_leader.user.name`**: Name of the user of the entry leader process.
757. **`process.entry_leader.user.name.text`**: Text representation of the user name of the entry leader process.
758. **`process.entry_leader.vpid`**: Virtual PID of the entry
759. **`process.entry_leader.working_directory`**: Working directory of the entry leader process.
760. **`process.entry_leader.working_directory.text`**: Text representation of the entry leader's working directory.
761. **`process.env_vars`**: Environment variables of the process.
762. **`process.executable`**: Executable of the process.
763. **`process.executable.caseless`**: Caseless version of the process executable.
764. **`process.executable.text`**: Text representation of the process executable.
765. **`process.exit_code`**: Exit code of the process.
766. **`process.group_leader.args`**: Arguments of the group leader process.
767. **`process.group_leader.args_count`**: Number of arguments of the group leader process.
768. **`process.group_leader.command_line`**: Command line of the group leader process.
769. **`process.group_leader.command_line.text`**: Text representation of the group leader's command line.
770. **`process.group_leader.entity_id`**: Entity ID of the group leader process.
771. **`process.group_leader.executable`**: Executable of the group leader process.
772. **`process.group_leader.executable.text`**: Text representation of the group leader's executable.
773. **`process.group_leader.group.id`**: ID of the group of the group leader process.
774. **`process.group_leader.group.name`**: Name of the group of the group leader process.
775. **`process.group_leader.interactive`**: Whether the group leader process is interactive.
776. **`process.group_leader.name`**: Name of the group leader process.
777. **`process.group_leader.name.text`**: Text representation of the group leader's name.
778. **`process.group_leader.pid`**: PID of the group leader process.
779. **`process.group_leader.real_group.id`**: ID of the real group of the group leader process.
780. **`process.group_leader.real_group.name`**: Name of the real group of the group leader process.
781. **`process.group_leader.real_user.id`**: ID of the real user of the group leader process.
782. **`process.group_leader.real_user.name`**: Name of the real user of the group leader process.
783. **`process.group_leader.real_user.name.text`**: Text representation of the real user name of the group leader process.
784. **`process.group_leader.same_as_process`**: Whether the group leader is the same as the process.
785. **`process.group_leader.saved_group.id`**: ID of the saved group of the group leader process.
786. **`process.group_leader.saved_group.name`**: Name of the saved group of the group leader process.
787. **`process.group_leader.saved_user.id`**: ID of the saved user of the group leader process.
788. **`process.group_leader.saved_user.name`**: Name of the saved user of the group leader process.
789. **`process.group_leader.saved_user.name.text`**: Text representation of the saved user name of the group leader process.
790. **`process.group_leader.start`**: Start time of the group leader process.
791. **`process.group_leader.supplemental_groups.id`**: IDs of supplemental groups of the group leader process.
792. **`process.group_leader.supplemental_groups.name`**: Names of supplemental groups of the group leader process.
793. **`process.group_leader.tty.char_device.major`**: Major number of the character device associated with the group leader's TTY.
794. **`process.group_leader.tty.char_device.minor`**: Minor number of the character device associated with the group leader's TTY.
795. **`process.group_leader.user.id`**: ID of the user of the group leader process.
796. **`process.group_leader.user.name`**: Name of the user of the group leader process.
797. **`process.group_leader.user.name.text`**: Text representation of the user name of the group leader process.
798. **`process.group_leader.vpid`**: Virtual PID of the group leader process.
799. **`process.group_leader.working_directory`**: Working directory of the group leader process.
800. **`process.group_leader.working_directory.text`**: Text representation of the group leader's working directory.
801. **`process.hash.md5`**: MD5 hash of the process.
802. **`process.hash.sha1`**: SHA-1 hash of the process.
803. **`process.hash.sha256`**: SHA-256 hash of the process.
804. **`process.hash.sha384`**: SHA-384 hash of the process.
805. **`process.hash.sha512`**: SHA-512 hash of the process.
806. **`process.hash.ssdeep`**: ssdeep hash of the process.
807. **`process.hash.tlsh`**: tlsh hash of the process.
808. **`process.interactive`**: Whether the process is interactive.
809. **`process.io.bytes_skipped.length`**: Length of bytes skipped during I/O.
810. **`process.io.bytes_skipped.offset`**: Offset of bytes skipped during I/O.
811. **`process.io.max_bytes_per_process_exceeded`**: Whether the maximum bytes per process were exceeded during I/O.
812. **`process.io.text`**: Text representation of I/O data.
813. **`process.io.total_bytes_captured`**: Total bytes captured during I/O.
814. **`process.io.total_bytes_skipped`**: Total bytes skipped during I/O.
815. **`process.io.type`**: Type of I/O operation.
816. **`process.macho.go_import_hash`**: Hash of Go imports in the Mach-O file associated with the process.
817. **`process.macho.go_imports`**: Go imports in the Mach-O file associated with the process.
818. **`process.macho.go_imports_names_entropy`**: Entropy of Go import names in the Mach-O file associated with the process.
819. **`process.macho.go_imports_names_var_entropy`**: Variable entropy of Go import names in the Mach-O file associated with the process.
820. **`process.macho.go_stripped`**: Whether Go symbols are stripped in the Mach-O file associated with the process.
821. **`process.macho.import_hash`**: Import hash of the Mach-O file associated with the process.
822. **`process.macho.imports`**: Imports in the Mach-O file associated with the process.
823. **`process.macho.imports_names_entropy`**: Entropy of import names in the Mach-O file associated with the process.
824. **`process.macho.imports_names_var_entropy`**: Variable entropy of import names in the Mach-O file associated with the process.
825. **`process.macho.sections.entropy`**: Entropy of sections in the Mach-O file associated with the process.
826. **`process.macho.sections.name`**: Names of sections in the Mach-O file associated with the process.
827. **`process.macho.sections.physical_size`**: Physical size of sections in the Mach-O file associated with the process.
828. **`process.macho.sections.var_entropy`**: Variable entropy of sections in the Mach-O file associated with the process.
829. **`process.macho.sections.virtual_size`**: Virtual size of sections in the Mach-O file associated with the process.
830. **`process.macho.symhash`**: Symhash of the Mach-O file associated with the process.
831. **`process.name`**: Name of the process.
832. **`process.name.caseless`**: Caseless version of the process name.
833. **`process.name.text`**: Text representation of the process name.
834. **`process.parent.args`**: Arguments of the parent process.
835. **`process.parent.args_count`**: Number of arguments of the parent process.
836. **`process.parent.code_signature.digest_algorithm`**: Algorithm used for code signing the parent process.
837. **`process.parent.code_signature.exists`**: Whether a code signature exists for the parent process.
838. **`process.parent.code_signature.signing_id`**: Signing ID of the parent process's code signature.
839. **`process.parent.code_signature.status`**: Status of the parent process's code signature.
840. **`process.parent.code_signature.subject_name`**: Subject name of the parent process's code signature.
841. **`process.parent.code_signature.team_id`**: Team ID of the parent process's code signature.
842. **`process.parent.code_signature.timestamp`**: Timestamp of the parent process's code signature.
843. **`process.parent.code_signature.trusted`**: Whether the parent process's code signature is trusted.
844. **`process.parent.code_signature.valid`**: Whether the parent process's code signature is valid.
845. **`process.parent.command_line`**: Command line of the parent process.
846. **`process.parent.command_line.text`**: Text representation of the parent process's command line.
847. **`process.parent.elf.architecture`**: Architecture of the ELF file associated with the parent process.
848. **`process.parent.elf.byte_order`**: Byte order of the ELF file associated with the parent process.
849. **`process.parent.elf.cpu_type`**: CPU type of the ELF file associated with the parent process.
850. **`process.parent.elf.creation_date`**: Creation date of the ELF file associated with the parent process.
851. **`process.parent.elf.exports`**: Exports in the ELF file associated with the parent process.
852. **`process.parent.elf.go_import_hash`**: Hash of Go imports in the ELF file associated with the parent process.
853. **`process.parent.elf.go_imports`**: Go imports in the ELF file associated with the parent process.
854. **`process.parent.elf.go_imports_names_entropy`**: Entropy of Go import names in the ELF file associated with the parent process.
855. **`process.parent.elf.go_imports_names_var_entropy`**: Variable entropy of Go import names in the ELF file associated with the parent process.
856. **`process.parent.elf.go_stripped`**: Whether Go symbols are stripped in the ELF file associated with the parent process.
857. **`process.parent.elf.header.abi_version`**: ABI version in the ELF file header associated with the parent process.
858. **`process.parent.elf.header.class`**: Class in the ELF file header associated with the parent process.
859. **`process.parent.elf.header.data`**: Data in the ELF file header associated with the parent process.
860. **`process.parent.elf.header.entrypoint`**: Entry point in the ELF file header associated with the parent process.
861. **`process.parent.elf.header.object_version`**: Object version in the ELF file header associated with the parent process.
862. **`process.parent.elf.header.os_abi`**: OS ABI in the ELF file header associated with the parent process.
863. **`process.parent.elf.header.type`**: Type in the ELF file header associated with the parent process.
864. **`process.parent.elf.header.version`**: Version in the ELF file header associated with the parent process.
865. **`process.parent.elf.import_hash`**: Import hash of the ELF file associated with the parent process.
866. **`process.parent.elf.imports`**: Imports in the ELF file associated with the parent process.
867. **`process.parent.elf.imports_names_entropy`**: Entropy of import names in the ELF file associated with the parent process.
868. **`process.parent.elf.imports_names_var_entropy`**: Variable entropy of import names in the ELF file associated with the parent process.
869. **`process.parent.elf.sections.chi2`**: Chi-squared value of sections in the ELF file associated with the parent process.
870. **`process.parent.elf.sections.entropy`**: Entropy of sections in the ELF file associated with the parent process.
871. **`process.parent.elf.sections.flags`**: Flags of sections in the ELF file associated with the parent process.
872. **`process.parent.elf.sections.name`**: Names of sections in the ELF file associated with the parent process.
873. **`process.parent.elf.sections.physical_offset`**: Physical offset of sections in the ELF file associated with the parent process.
874. **`process.parent.elf.sections.physical_size`**: Physical size of sections in the ELF file associated with the parent process.
875. **`process.parent.elf.sections.type`**: Type of sections in the ELF file associated with the parent process.
876. **`process.parent.elf.sections.var_entropy`**: Variable entropy of sections in the ELF file associated with the parent process.
877. **`process.parent.elf.sections.virtual_address`**: Virtual address of sections in the ELF file associated with the parent process.
878. **`process.parent.elf.sections.virtual_size`**: Virtual size of sections in the ELF file associated with the parent process.
879. **`process.parent.elf.segments.sections`**: Sections in ELF segments associated with the parent process.
880. **`process.parent.elf.segments.type`**: Type of ELF segments associated with the parent process.
881. **`process.parent.elf.shared_libraries`**: Shared libraries in the ELF file associated with the parent process.
882. **`process.parent.elf.telfhash`**: Telfhash of the ELF file associated with the parent process.
883. **`process.parent.end`**: Timestamp when the parent process ended.
884. **`process.parent.entity_id`**: Entity ID of the parent process.
885. **`process.parent.executable`**: Executable of the parent process.
886. **`process.parent.executable.text`**: Text representation of the parent process's executable.
887. **`process.parent.exit_code`**: Exit code of the parent process.
888. **`process.parent.group.id`**: ID of the group of the parent process.
889. **`process.parent.group_leader.entity_id`**: Entity ID of the group leader of the parent process.
890. **`process.parent.group_leader.pid`**: PID of the group leader of the parent process.
891. **`process.parent.group_leader.start`**: Start time of the group leader of the parent process.
892. **`process.parent.group_leader.vpid`**: Virtual PID of the group leader of the parent process.
893. **`process.parent.group.name`**: Name of the group of the parent process.
894. **`process.parent.hash.md5`**: MD5 hash of the parent process.
895. **`process.parent.hash.sha1`**: SHA-1 hash of the parent process.
896. **`process.parent.hash.sha256`**: SHA-256 hash of the parent process.
897. **`process.parent.hash.sha384`**: SHA-384 hash of the parent process.
898. **`process.parent.hash.sha512`**: SHA-512 hash of the parent process.
899. **`process.parent.hash.ssdeep`**: ssdeep hash of the parent process.
900. **`process.parent.hash.tlsh`**: tlsh hash of the parent process.
901. **`process.parent.interactive`**: Whether the parent process is interactive.
902. **`process.parent.macho.go_import_hash`**: Hash of Go imports in the Mach-O file associated with the parent process.
903. **`process.parent.macho.go_imports`**: Go imports in the Mach-O file associated with the parent process.
904. **`process.parent.macho.go_imports_names_entropy`**: Entropy of Go import names in the Mach-O file associated with the parent process.
905. **`process.parent.macho.go_imports_names_var_entropy`**: Variable entropy of Go import names in the Mach-O file associated with the parent process.
906. **`process.parent.macho.go_stripped`**: Whether Go symbols are stripped in the Mach-O file associated with the parent process.
907. **`process.parent.macho.import_hash`**: Import hash of the Mach-O file associated with the parent process.
908. **`process.parent.macho.imports`**: Imports in the Mach-O file associated with the parent process.
909. **`process.parent.macho.imports_names_entropy`**: Entropy of import names in the Mach-O file associated with the parent process.
910. **`process.parent.macho.imports_names_var_entropy`**: Variable entropy of import names in the Mach-O file associated with the parent process.
911. **`process.parent.macho.sections.entropy`**: Entropy of sections in the Mach-O file associated with the parent process.
912. **`process.parent.macho.sections.name`**: Names of sections in the Mach-O file associated with the parent process.
913. **`process.parent.macho.sections.physical_size`**: Physical size of sections in the Mach-O file associated with the parent process.
914. **`process.parent.macho.sections.var_entropy`**: Variable entropy of sections in the Mach-O file associated with the parent process.
915. **`process.parent.macho.sections.virtual_size`**: Virtual size of sections in the Mach-O file associated with the parent process.
916. **`process.parent.macho.symhash`**: Symhash of the Mach-O file associated with the parent process.
917. **`process.parent.name`**: Name of the parent process.
918. **`process.parent.name.text`**: Text representation of the parent process's name.
919. **`process.parent.pe.architecture`**: Architecture of the PE file associated with the parent process.
920. **`process.parent.pe.company`**: Company name in the PE file associated with the parent process.
921. **`process.parent.pe.description`**: Description in the PE file associated with the parent process.
922. **`process.parent.pe.file_version`**: File version in the PE file associated with the parent process.
923. **`process.parent.pe.go_import_hash`**: Hash of Go imports in the PE file associated with the parent process.
924. **`process.parent.pe.go_imports`**: Go imports in the PE file associated with the parent process.
925. **`process.parent.pe.go_imports_names_entropy`**: Entropy of Go import names in the PE file associated with the parent process.
926. **`process.parent.pe.go_imports_names_var_entropy`**: Variable entropy of Go import names in the PE file associated with the parent process.
927. **`process.parent.pe.go_stripped`**: Whether Go symbols are stripped in the PE file associated with the parent process.
928. **`process.parent.pe.imphash`**: Import hash of the PE file associated with the parent process.
929. **`process.parent.pe.import_hash`**: Import hash of the PE file associated with the parent process.
930. **`process.parent.pe.imports`**: Imports in the PE file associated with the parent process.
931. **`process.parent.pe.imports_names_entropy`**: Entropy of import names in the PE file associated with the parent process.
932. **`process.parent.pe.imports_names_var_entropy`**: Variable entropy of import names in the PE file associated with the parent process.
933. **`process.parent.user.id`**: ID of the user of the parent process.
934. **`process.parent.user.name`**: Name of the user of the parent process.
935. **`process.parent.user.name.text`**: Text representation of the user name of the parent process.
936. **`process.parent.vpid`**: Virtual PID of the parent process.
937. **`process.parent.working_directory`**: Working directory of the parent process.
938. **`process.parent.working_directory.text`**: Text representation of the parent process's working directory.
939. **`process.pe.architecture`**: Architecture of the PE file associated with the process.
940. **`process.pe.company`**: Company name in the PE file associated with the process.
941. **`process.pe.description`**: Description in the PE file associated with the process.
942. **`process.pe.file_version`**: File version in the PE file associated with the process.
943. **`process.pe.go_import_hash`**: Hash of Go imports in the PE file associated with the process.
944. **`process.pe.go_imports`**: Go imports in the PE file associated with the process.
945. **`process.pe.go_imports_names_entropy`**: Entropy of Go import names in the PE file associated with the process.
946. **`process.pe.go_imports_names_var_entropy`**: Variable entropy of Go import names in the PE file associated with the process.
947. **`process.pe.go_stripped`**: Whether Go symbols are stripped in the PE file associated with the process.
948. **`process.pe.imphash`**: Import hash of the PE file associated with the process.
949. **`process.pe.import_hash`**: Import hash of the PE file associated with the process.
950. **`process.pe.imports`**: Imports in the PE file associated with the process.
951. **`process.pe.imports_names_entropy`**: Entropy of import names in the PE file associated with the process.
952. **`process.pe.imports_names_var_entropy`**: Variable entropy of import names in the PE file associated with the process.
953. **`process.pe.original_file_name`**: Original file name in the PE file associated with the process.
954. **`process.pe.pehash`**: PE hash of the file associated with the process.
955. **`process.pe.product`**: Product name in the PE file associated with the process.
956. **`process.pe.sections.entropy`**: Entropy of sections in the PE file associated with the process.
957. **`process.pe.sections.name`**: Names of sections in the PE file associated with the process.
958. **`process.pe.sections.physical_size`**: Physical size of sections in the PE file associated with the process.
959. **`process.pe.sections.var_entropy`**: Variable entropy of sections in the PE file associated with the process.
960. **`process.pe.sections.virtual_size`**: Virtual size of sections in the PE file associated with the process.
961. **`process.pgid`**: Process group ID.
962. **`process.pid`**: Process ID.
963. **`process.previous.args`**: Arguments of the previous process.
964. **`process.previous.args_count`**: Number of arguments of the previous process.
965. **`process.previous.executable`**: Executable of the previous process.
966. **`process.previous.executable.text`**: Text representation of the previous process's executable.
967. **`process.real_group.id`**: ID of the real group of the process.
968. **`process.real_group.name`**: Name of the real group of the process.
969. **`process.real_user.id`**: ID of the real user of the process.
970. **`process.real_user.name`**: Name of the real user of the process.
971. **`process.real_user.name.text`**: Text representation of the real user name of the process.
972. **`process.saved_group.id`**: ID of the saved group of the process.
973. **`process.saved_group.name`**: Name of the saved group of the process.
974. **`process.saved_user.id`**: ID of the saved user of the process.
975. **`process.saved_user.name`**: Name of the saved user of the process.
976. **`process.saved_user.name.text`**: Text representation of the saved user name of the process.
977. **`process.session_leader.args`**: Arguments of the session leader process.
978. **`process.session_leader.args_count`**: Number of arguments of the session leader process.
979. **`process.session_leader.command_line`**: Command line of the session leader process.
980. **`process.session_leader.command_line.text`**: Text representation of the session leader's command line.
981. **`process.session_leader.entity_id`**: Entity ID of the session leader process.
982. **`process.session_leader.executable`**: Executable of the session leader process.
983. **`process.session_leader.executable.text`**: Text representation of the session leader's executable.
984. **`process.session_leader.group.id`**: ID of the group of the session leader process.
985. **`process.session_leader.group.name`**: Name of the group of the session leader process.
986. **`process.session_leader.interactive`**: Whether the session leader process is interactive.
987. **`process.session_leader.name`**: Name of the session leader process.
988. **`process.session_leader.name.text`**: Text representation of the session leader's name.
989. **`process.session_leader.parent.entity_id`**: Entity ID of the parent of the session leader process.
990. **`process.session_leader.parent.pid`**: PID of the parent of the session leader process.
991. **`process.session_leader.parent.session_leader.entity_id`**: Entity ID of the session leader parent process.
992. **`process.session_leader.parent.session_leader.pid`**: PID of the session leader parent process.
993. **`process.session_leader.parent.session_leader.start`**: Start time of the session leader parent process.
994. **`process.session_leader.parent.session_leader.vpid`**: Virtual PID of the session leader parent process.
995. **`process.session_leader.parent.start`**: Start time of the parent of the session leader process.
996. **`process.session_leader.parent.vpid`**: Virtual PID of the parent of the session leader process.
997. **`process.session_leader.pid`**: PID of the session leader process.
998. **`process.session_leader.real_group.id`**: ID of the real group of the session leader process.
999. **`process.session_leader.real_group.name`**: Name of the real group of the session leader process.
1000. **`process.session_leader.real_user.id`**: ID of the real user of the session leader process.
1001. **`process.session_leader.real_user.name`**: Name of the real user of the session leader process.
1002. **`process.session_leader.real_user.name.text`**: Text representation of the real user name of the session leader process.
1003. **`process.session_leader.same_as_process`**: Whether the session leader is the same as the process.
1004. **`process.session_leader.saved_group.id`**: ID of the saved group of the session leader process.
1005. **`process.session_leader.saved_group.name`**: Name of the saved group of the session leader process.
1006. **`process.session_leader.saved_user.id`**: ID of the saved user of the session leader process.
1007. **`process.session_leader.saved_user.name`**: Name of the saved user of the session leader process.
1008. **`process.session_leader.saved_user.name.text`**: Text representation of the saved user name of the session leader process.
1009. **`process.session_leader.start`**: Start time of the session leader process.
1010. **`process.session_leader.supplemental_groups.id`**: IDs of supplemental groups of the session leader process.
1011. **`process.session_leader.supplemental_groups.name`**: Names of supplemental groups of the session leader process.
1012. **`process.session_leader.tty.char_device.major`**: Major number of the character device associated with the session leader's TTY.
1013. **`process.session_leader.tty.char_device.minor`**: Minor number of the character device associated with the session leader's TTY.
1014. **`process.session_leader.user.id`**: ID of the user of the session leader process.
1015. **`process.session_leader.user.name`**: Name of the user of the session leader process.
1016. **`process.session_leader.user.name.text`**: Text representation of the user name of the session leader process.
1017. **`process.session_leader.vpid`**: Virtual PID of the session leader process.
1018. **`process.session_leader.working_directory`**: Working directory of the session leader process.
1019. **`process.session_leader.working_directory.text`**: Text representation of the session leader's working directory.
1020. **`process.start`**: Start time of the process.
1021. **`process.supplemental_groups.id`**: IDs of supplemental groups of the process.
1022. **`process.supplemental_groups.name`**: Names of supplemental groups of the process.
1023. **`process.thread.capabilities.effective`**: Effective capabilities of the process thread.
1024. **`process.thread.capabilities.permitted`**: Permitted capabilities of the process thread.
1025. **`process.thread.id`**: ID of the process thread.
1026. **`process.thread.name`**: Name of the process thread.
1027. **`process.title`**: Title of the process.
1028. **`process.title.text`**: Text representation of the process title.
1029. **`process.tty.char_device.major`**: Major number of the character device associated with the process's TTY.
1030. **`process.tty.char_device.minor`**: Minor number of the character device associated with the process's TTY.
1031. **`process.tty.columns`**: Number of columns in the process's TTY.
1032. **`process.tty.rows`**: Number of rows in the process's TTY.
1033. **`process.uptime`**: Uptime of the process.
1034. **`process.user.id`**: ID of the user of the process.
1035. **`process.user.name`**: Name of the user of the process.
1036. **`process.user.name.text`**: Text representation of the user name of the process.
1037. **`process.vpid`**: Virtual PID of the process.
1038. **`process.working_directory`**: Working directory of the process.
1039. **`process.working_directory.text`**: Text representation of the process's working directory.
1040. **`registry.data.bytes`**: Byte data stored in the registry.
1041. **`registry.data.strings`**: String data stored in the registry.
1042. **`registry.data.type`**: Type of data stored in the registry.
1043. **`registry.hive`**: Hive of the registry.
1044. **`registry.key`**: Key in the registry.
1045. **`registry.path`**: Path to the registry key.
1046. **`registry.value`**: Value associated with the registry key.
1047. **`related.hash`**: Hash of related data.
1048. **`related.hosts`**: Hosts related to the event.
1049. **`related.ip`**: IP addresses related to the event.
1050. **`related.user`**: Users related to the event.
1051. **`rule.author`**: Author of the rule.
1052. **`rule.category`**: Category of the rule.
1053. **`rule.description`**: Description of the rule.
1054. **`rule.id`**: ID of the rule.
1055. **`rule.license`**: License associated with the rule.
1056. **`rule.name`**: Name of the rule.
1057. **`rule.reference`**: Reference associated with the rule.
1058. **`rule.ruleset`**: Ruleset that the rule belongs to.
1059. **`rule.uuid`**: UUID of the rule.
1060. **`rule.version`**: Version of the rule.
1061. **`_score`**: Relevance score of the document.
1062. **`Security`**: This field seems to be a placeholder or category; more context is needed.
1063. **`server.address`**: Address of the server.
1064. **`server.as.number`**: Autonomous System (AS) number of the server.
1065. **`server.as.organization.name`**: Name of the organization associated with the server's AS.
1066. **`server.as.organization.name.text`**: Text representation of the server's AS organization name.
1067. **`server.bytes`**: Number of bytes sent by the server.
1068. **`server.domain`**: Domain of the server.
1069. **`server.geo.city_name`**: City name of the server's location.
1070. **`server.geo.continent_code`**: Continent code of the server's location.
1071. **`server.geo.continent_name`**: Continent name of the server's location.
1072. **`server.geo.country_iso_code`**: ISO code of the server's country.
1073. **`server.geo.country_name`**: Name of the server's country.
1074. **`server.geo.location`**: Geographic location of the server.
1075. **`server.geo.name`**: Name of the server's geographic location.
1076. **`server.geo.postal_code`**: Postal code of the server's location.
1077. **`server.geo.region_iso_code`**: ISO code of the server's region.
1078. **`server.geo.region_name`**: Name of the server's region.
1079. **`server.geo.timezone`**: Time zone of the server's location.
1080. **`server.ip`**: IP address of the server.
1081. **`server.mac`**: MAC address of the server.
1082. **`server.nat.ip`**: NAT IP address of the server.
1083. **`server.nat.port`**: NAT port of the server.
1084. **`server.packets`**: Number of packets sent by the server.
1085. **`server.port`**: Port used by the server.
1086. **`server.registered_domain`**: Registered domain of the server.
1087. **`server.subdomain`**: Subdomain of the server.
1088. **`server.top_level_domain`**: Top-level domain of the server.
1089. **`server.user.domain`**: Domain of the server user.
1090. **`server.user.email`**: Email address of the server user.
1091. **`server.user.full_name`**: Full name of the server user.
1092. **`server.user.full_name.text`**: Text representation of the server user's full name.
1093. **`server.user.group.domain`**: Domain of the server user's group.
1094. **`server.user.group.id`**: ID of the server user's group.
1095. **`server.user.group.name`**: Name of the server user's group.
1096. **`server.user.hash`**: Hash of the server user's credentials.
1097. **`server.user.id`**: ID of the server user.
1098. **`server.user.name`**: Name of the server user.
1099. **`server.user.name.text`**: Text representation of the server user's name.
1100. **`server.user.roles`**: Roles of the server user.
1101. **`service.address`**: Address of the service.
1102. **`service.environment`**: Environment of the service.
1103. **`service.ephemeral_id`**: Ephemeral ID of the service.
1104. **`service.id`**: ID of the service.
1105. **`service.name`**: Name of the service.
1106. **`service.node.name`**: Name of the node running the service.
1107. **`service.node.role`**: Role of the node running the service.
1108. **`service.node.roles`**: Roles of the node running the service.
1109. **`service.origin.address`**: Address of the service origin.
1110. **`service.origin.environment`**: Environment of the service origin.
1111. **`service.origin.ephemeral_id`**: Ephemeral ID of the service origin.
1112. **`service.origin.id`**: ID of the service origin.
1113. **`service.origin.name`**: Name of the service origin.
1114. **`service.origin.node.name`**: Name of the node running the service origin.
1115. **`service.origin.node.role`**: Role of the node running the service origin.
1116. **`service.origin.node.roles`**: Roles of the node running the service origin.
1117. **`service.origin.state`**: State of the service origin.
1118. **`service.origin.type`**: Type of the service origin.
1119. **`service.origin.version`**: Version of the service origin.
1120. **`service.state`**: State of the service.
1121. **`service.target.address`**: Address of the service target.
1122. **`service.target.environment`**: Environment of the service target.
1123. **`service.target.ephemeral_id`**: Ephemeral ID of the service target.
1124. **`service.target.id`**: ID of the service target.
1125. **`service.target.name`**: Name of the service target.
1126. **`service.target.node.name`**: Name of the node running the service target.
1127. **`service.target.node.role`**: Role of the node running the service target.
1128. **`service.target.node.roles`**: Roles of the node running the service target.
1129. **`service.target.state`**: State of the service target.
1130. **`service.target.type`**: Type of the service target.
1131. **`service.target.version`**: Version of the service target.
1132. **`service.type`**: Type of the service.
1133. **`service.version`**: Version of the service.
1134. **`signal.ancestors.depth`**: Depth of the signal's ancestors.
1135. **`signal.ancestors.id`**: IDs of the signal's ancestors.
1136. **`signal.ancestors.index`**: Index of the signal's ancestors.
1137. **`signal.ancestors.type`**: Type of the signal's ancestors.
1138. **`signal.depth`**: Depth of the signal.
1139. **`signal.group.id`**: ID of the group associated with the signal.
1140. **`signal.group.index`**: Index of the group associated with the signal.
1141. **`signal.original_event.action`**: Action of the original event associated with the signal.
1142. **`signal.original_event.category`**: Category of the original event associated with the signal.
1143. **`signal.original_event.code`**: Code of the original event associated with the signal.
1144. **`signal.original_event.created`**: Timestamp when the original event was created.
1145. **`signal.original_event.dataset`**: Dataset of the original event associated with the signal.
1146. **`signal.original_event.duration`**: Duration of the original event associated with the signal.
1147. **`signal.original_event.end`**: End time of the original event associated with the signal.
1148. **`signal.original_event.hash`**: Hash of the original event associated with the signal.
1149. **`signal.original_event.id`**: ID of the original event associated with the signal.
1150. **`signal.original_event.kind`**: Kind of the original event associated with the signal.
1151. **`signal.original_event.module`**: Module associated with the original event.
1152. **`signal.original_event.outcome`**: Outcome of the original event associated with the signal.
1153. **`signal.original_event.provider`**: Provider of the original event associated with the signal.
1154. **`signal.original_event.reason`**: Reason for the original event associated with the signal.
1155. **`signal.original_event.risk_score`**: Risk score of the original event associated with the signal.
1156. **`signal.original_event.risk_score_norm`**: Normalized risk score of the original event associated with the signal.
1157. **`signal.original_event.sequence`**: Sequence number of the original event associated with the signal.
1158. **`signal.original_event.severity`**: Severity of the original event associated with the signal.
1159. **`signal.original_event.start`**: Start time of the original event associated with the signal.
1160. **`signal.original_event.timezone`**: Time zone of the original event associated with the signal.
1161. **`signal.original_event.type`**: Type of the original event associated with the signal.
1162. **`signal.original_time`**: Original time of the signal.
1163. **`signal.reason`**: Reason for the signal.
1164. **`signal.rule.author`**: Author of the rule that triggered the signal.
1165. **`signal.rule.building_block_type`**: Type of building block used in the rule.
1166. **`signal.rule.created_at`**: Timestamp when the rule was created.
1167. **`signal.rule.created_by`**: User who created the rule.
1168. **`signal.rule.description`**: Description of the rule.
1169. **`signal.rule.enabled`**: Whether the rule is enabled.
1170. **`signal.rule.false_positives`**: Number of false positives for the rule.
1171. **`signal.rule.from`**: From field in the rule.
1172. **`signal.rule.id`**: ID of the rule.
1173. **`signal.rule.immutable`**: Whether the rule is immutable.
1174. **`signal.rule.interval`**: Interval at which the rule is executed.
1175. **`signal.rule.license`**: License associated with the rule.
1176. **`signal.rule.max_signals`**: Maximum number of signals for the rule.
1177. **`signal.rule.name`**: Name of the rule.
1178. **`signal.rule.note`**: Note associated with the rule.
1179. **`signal.rule.references`**: References associated with the rule.
1180. **`signal.rule.risk_score`**: Risk score of the rule.
1181. **`signal.rule.rule_id`**: ID of the rule.
1182. **`signal.rule.rule_name_override`**: Override name for the rule.
1183. **`signal.rule.severity`**: Severity of the rule.
1184. **`signal.rule.tags`**: Tags associated with the rule.
1185. **`signal.rule.threat.framework`**: Threat framework associated with the rule.
1186. **`signal.rule.threat.tactic.id`**: ID of the threat tactic.
1187. **`signal.rule.threat.tactic.name`**: Name of the threat tactic.
1188. **`signal.rule.threat.tactic.reference`**: Reference for the threat tactic.
1189. **`signal.rule.threat.technique.id`**: ID of the threat technique.
1190. **`signal.rule.threat.technique.name`**: Name of the threat technique.
1191. **`signal.rule.threat.technique.reference`**: Reference for the threat technique.
1192. **`signal.rule.threat.technique.subtechnique.id`**: ID of the threat subtechnique.
1193. **`signal.rule.threat.technique.subtechnique.name`**: Name of the threat subtechnique.
1194. **`signal.rule.threat.technique.subtechnique.reference`**: Reference for the threat subtechnique.
1195. **`signal.rule.timeline_id`**: ID of the timeline associated with the rule.
1196. **`signal.rule.timeline_title`**: Title of the timeline associated with the rule.
1197. **`signal.rule.timestamp_override`**: Timestamp override for the rule.
1198. **`signal.rule.to`**: To field in the rule.
1199. **`signal.rule.type`**: Type of the rule.
1200. **`signal.rule.updated_at`**: Timestamp when the rule was updated.
1201. **`signal.rule.updated_by`**: User who updated the rule.
1202. **`signal.rule.version`**: Version of the rule.
1203. **`signal.status`**: Status of the signal.
1204. **`signal.threshold_result.cardinality.field`**: Field used for cardinality in threshold results.
1205. **`signal.threshold_result.cardinality.value`**: Value used for cardinality in threshold results.
1206. **`signal.threshold_result.count`**: Count of threshold results.
1207. **`signal.threshold_result.from`**: From field in threshold results.
1208. **`signal.threshold_result.terms.field`**: Field used for terms in threshold results.
1209. **`signal.threshold_result.terms.value`**: Value used for terms in threshold results.
1210. **`_source`**: Source document of the event.
1211. **`source.address`**: Address of the source.
1212. **`source.as.number`**: Autonomous System (AS) number of the source.
1213. **`source.as.organization.name`**: Name of the organization associated with the source's AS.
1214. **`source.as.organization.name.text`**: Text representation of the source's AS organization name.
1215. **`source.bytes`**: Number of bytes sent by the source.
1216. **`source.domain`**: Domain of the source.
1217. **`source.geo.city_name`**: City name of the source's location.
1218. **`source.geo.continent_code`**: Continent code of the source's location.
1219. **`source.geo.continent_name`**: Continent name of the source's location.
1220. **`source.geo.country_iso_code`**: ISO code of the source's country.
1221. **`source.geo.country_name`**: Name of the source's country.
1222. **`source.geo.location`**: Geographic location of the source.
1223. **`source.geo.name`**: Name of the source's geographic location.
1224. **`source.geo.postal_code`**: Postal code of the source's location.
1225. **`source.geo.region_iso_code`**: ISO code of the source's region.
1226. **`source.geo.region_name`**: Name of the source's region.
1227. **`source.geo.timezone`**: Time zone of the source's location.
1228. **`source.ip`**: IP address of the source.
1229. **`source.mac`**: MAC address of the source.
1230. **`source.nat.ip`**: NAT IP address of the source.
1231. **`source.nat.port`**: NAT port of the source.
1232. **`source.packets`**: Number of packets sent by the source.
1233. **`source.port`**: Port used by the source.
1234. **`source.registered_domain`**: Registered domain of the source.
1235. **`source.subdomain`**: Subdomain of the source.
1236. **`source.top_level_domain`**: Top-level domain of the source.
1237. **`source.user.domain`**: Domain of the source user.
1238. **`source.user.email`**: Email address of the source user.
1239. **`source.user.full_name`**: Full name of the source user.
1240. **`source.user.full_name.text`**: Text representation of the source user's full name.
1241. **`source.user.group.domain`**: Domain of the source user's group.
1242. **`source.user.group.id`**: ID of the source user's group.
1243. **`source.user.group.name`**: Name of the source user's group.
1244. **`source.user.hash`**: Hash of the source user's credentials.
1245. **`source.user.id`**: ID of the source user.
1246. **`source.user.name`**: Name of the source user.
1247. **`source.user.name.text`**: Text representation of the source user's name.
1248. **`source.user.roles`**: Roles of the source user.
1249. **`span.id`**: ID of the span.
1250. **`system.auth.ssh.dropped_ip`**: IP address dropped by SSH authentication.
1251. **`system.auth.ssh.event`**: SSH authentication event.
1252. **`system.auth.ssh.method`**: Method used for SSH authentication.
1253. **`system.auth.ssh.signature`**: Signature of the SSH authentication event.
1254. **`system.auth.sudo.command`**: Command executed with sudo.
1255. **`system.auth.sudo.error`**: Error message from sudo authentication.
1256. **`system.auth.sudo.pwd`**: Current working directory during sudo authentication.
1257. **`system.auth.sudo.tty`**: TTY device used during sudo authentication.
1258. **`system.auth.sudo.user`**: User who executed the sudo command.
1259. **`system.auth.syslog.version`**: Version of the syslog used for authentication.
1260. **`system.auth.useradd.home`**: Home directory of the user added.
1261. **`system.auth.useradd.shell`**: Shell assigned to the user added.
1262. **`tags`**: Tags associated with the event.
1263. **`threat.enrichments.indicator.as.number`**: Autonomous System (AS) number of the threat indicator.
1264. **`threat.enrichments.indicator.as.organization.name`**: Name of the organization associated with the threat indicator's AS.
1265. **`threat.enrichments.indicator.as.organization.name.text`**: Text representation of the threat indicator's AS organization name.
1266. **`threat.enrichments.indicator.confidence`**: Confidence level of the threat indicator.
1267. **`threat.enrichments.indicator.description`**: Description of the threat indicator.
1268. **`threat.enrichments.indicator.email.address`**: Email address associated with the threat indicator.
1269. **`threat.enrichments.indicator.file.accessed`**: Timestamp when the file associated with the threat indicator was last accessed.
1270. **`threat.enrichments.indicator.file.attributes`**: Attributes of the file associated with the threat indicator.
1271. **`threat.enrichments.indicator.file.code_signature.digest_algorithm`**: Algorithm used for code signing the file associated with the threat indicator.
1272. **`threat.enrichments.indicator.file.code_signature.exists`**: Whether a code signature exists for the file associated with the threat indicator.
1273. **`threat.enrichments.indicator.file.code_signature.signing_id`**: Signing ID of the file's code signature associated with the threat indicator.
1274. **`threat.enrichments.indicator.file.code_signature.status`**: Status of the file's code signature associated with the threat indicator.
1275. **`threat.enrichments.indicator.file.code_signature.subject_name`**: Subject name of the file's code signature associated with the threat indicator.
1276. **`threat.enrichments.indicator.file.code_signature.team_id`**: Team ID of the file's code signature associated with the threat indicator.
1277. **`threat.enrichments.indicator.file.code_signature.timestamp`**: Timestamp of the file's code signature associated with the threat indicator.
1278. **`threat.enrichments.indicator.file.code_signature.trusted`**: Whether the file's code signature associated with the threat indicator is trusted.
1279. **`threat.enrichments.indicator.file.code_signature.valid`**: Whether the file's code signature associated with the threat indicator is valid.
1280. **`threat.enrichments.indicator.file.created`**: Timestamp when the file associated with the threat indicator was created.
1281. **`threat.enrichments.indicator.file.ctime`**: Timestamp when the file's metadata was last changed.
1282. **`threat.enrichments.indicator.file.device`**: Device where the file associated with the threat indicator resides.
1283. **`threat.enrichments.indicator.file.directory`**: Directory of the file associated with the threat indicator.
1284. **`threat.enrichments.indicator.file.drive_letter`**: Drive letter of the file associated with the threat indicator.
1285. **`threat.enrichments.indicator.file.elf.architecture`**: Architecture of the ELF file associated with the threat indicator.
1286. **`threat.enrichments.indicator.file.elf.byte_order`**: Byte order of the ELF file associated with the threat indicator.
1287. **`threat.enrichments.indicator.file.elf.cpu_type`**: CPU type of the ELF file associated with the threat indicator.
1288. **`threat.enrichments.indicator.file.elf.creation_date`**: Creation date of the ELF file associated with the threat indicator.
1289. **`threat.enrichments.indicator.file.elf.exports`**: Exports in the ELF file associated with the threat indicator.
1290. **`threat.enrichments.indicator.file.elf.go_import_hash`**: Hash of Go imports in the ELF file associated with the threat indicator.
1291. **`threat.enrichments.indicator.file.elf.go_imports`**: Go imports in the ELF file associated with the threat indicator.
1292. **`threat.enrichments.indicator.file.elf.go_imports_names_entropy`**: Entropy of Go import names in the ELF file associated with the threat indicator.
1293. **`threat.enrichments.indicator.file.elf.go_imports_names_var_entropy`**: Variable entropy of Go import names in the ELF file associated with the threat indicator.
1294. **`threat.enrichments.indicator.file.elf.go_stripped`**: Whether Go symbols are stripped in the ELF file associated with the threat indicator.
1295. **`threat.enrichments.indicator.file.elf.header.abi_version`**: ABI version in the ELF file header associated with the threat indicator.
1296. **`threat.enrichments.indicator.file.elf.header.class`**: Class in the ELF file header associated with the threat indicator.
1297. **`threat.enrichments.indicator.file.elf.header.data`**: Data in the ELF file header associated with the threat indicator.
1298. **`threat.enrichments.indicator.file.elf.header.entrypoint`**: Entry point in the ELF file header associated with the threat indicator.
1299. **`threat.enrichments.indicator.file.elf.header.object_version`**: Object version in the ELF file header associated with the threat indicator.
1300. **`threat.enrichments.indicator.file.elf.header.os_abi`**: OS ABI in the ELF file header associated with the threat indicator.
1301. **`threat.enrichments.indicator.file.elf.header.type`**: Type in the ELF file header associated with the threat indicator.
1302. **`threat.enrichments.indicator.file.elf.header.version`**: Version in the ELF file header associated with the threat indicator.
1303. **`threat.enrichments.indicator.file.elf.import_hash`**: Import hash of the ELF file associated with the threat indicator.
1304. **`threat.enrichments.indicator.file.elf.imports`**: Imports in the ELF file associated with the threat indicator.
1305. **`threat.enrichments.indicator.file.elf.imports_names_entropy`**: Entropy of import names in the ELF file associated with the threat indicator.
1306. **`threat.enrichments.indicator.file.elf.imports_names_var_entropy`**: Variable entropy of import names in the ELF file associated with the threat indicator.
1307. **`threat.enrichments.indicator.file.elf.sections.chi2`**: Chi-squared value of sections in the ELF file associated with the threat indicator.
1308. **`threat.enrichments.indicator.file.elf.sections.entropy`**: Entropy of sections in the ELF file associated with the threat indicator.
1309. **`threat.enrichments.indicator.file.elf.sections.flags`**: Flags of sections in the ELF file associated with the threat indicator.
1310. **`threat.enrichments.indicator.file.elf.sections.name`**: Names of sections in the ELF file associated with the threat indicator.
1311. **`threat.enrichments.indicator.file.elf.sections.physical_offset`**: Physical offset of sections in the ELF file associated with the threat indicator.
1312. **`threat.enrichments.indicator.file.elf.sections.physical_size`**: Physical size of sections in the ELF file associated with the threat indicator.
1313. **`threat.enrichments.indicator.file.elf.sections.type`**: Type of sections in the ELF file associated with the threat indicator.
1314. **`threat.enrichments.indicator.file.elf.sections.var_entropy`**: Variable entropy of sections in the ELF file associated with the threat indicator.
1315. **`threat.enrichments.indicator.file.elf.sections.virtual_address`**: Virtual address of sections in the ELF file associated with the threat indicator.
1316. **`threat.enrichments.indicator.file.elf.sections.virtual_size`**: Virtual size of sections in the ELF file associated with the threat indicator.
1317. **`threat.enrichments.indicator.file.elf.segments.sections`**: Sections in ELF segments associated with the threat indicator.
1318. **`threat.enrichments.indicator.file.elf.segments.type`**: Type of ELF segments associated with the threat indicator.
1319. **`threat.enrichments.indicator.file.elf.shared_libraries`**: Shared libraries in the ELF file associated with the threat indicator.
1320. **`threat.enrichments.indicator.file.elf.telfhash`**: Telfhash of the ELF file associated with the threat indicator.
1321. **`threat.enrichments.indicator.file.extension`**: File extension of the file associated with the threat indicator.
1322. **`threat.enrichments.indicator.file.fork_name`**: Name of the file fork associated with the threat indicator.
1323. **`threat.enrichments.indicator.file.gid`**: Group ID of the file owner associated with the threat indicator.
1324. **`threat.enrichments.indicator.file.group`**: Group name of the file owner associated with the threat indicator.
1325. **`threat.enrichments.indicator.file.hash.md5`**: MD5 hash of the file associated with the threat indicator.
1326. **`threat.enrichments.indicator.file.hash.sha1`**: SHA-1 hash of the file associated with the threat indicator.
1327. **`threat.enrichments.indicator.file.hash.sha256`**: SHA-256 hash of the file associated with the threat indicator.
1328. **`threat.enrichments.indicator.file.hash.sha384`**: SHA-384 hash of the file associated with the threat indicator.
1329. **`threat.enrichments.indicator.file.hash.sha512`**: SHA-512 hash of the file associated with the threat indicator.
1330. **`threat.enrichments.indicator.file.hash.ssdeep`**: ssdeep hash of the file associated with the threat indicator.
1331. **`threat.enrichments.indicator.file.hash.tlsh`**: tlsh hash of the file associated with the threat indicator.
1332. **`threat.enrichments.indicator.file.inode`**: Inode number of the file associated with the threat indicator.
1333. **`threat.enrichments.indicator.file.mime_type`**: MIME type of the file associated with the threat indicator.
1334. **`threat.enrichments.indicator.file.mode`**: File mode (permissions) of the file associated with the threat indicator.
1335. **`threat.enrichments.indicator.file.mtime`**: Timestamp when the file's contents were last modified.
1336. **`threat.enrichments.indicator.file.name`**: Name of the file associated with the threat indicator.
1337. **`threat.enrichments.indicator.file.owner`**: Owner of the file associated with the threat indicator.
1338. **`threat.enrichments.indicator.file.path`**: Path to the file associated with the threat indicator.
1339. **`threat.enrichments.indicator.file.path.text`**: Text representation of the file path associated with the threat indicator.
1340. **`threat.enrichments.indicator.file.pe.architecture`**: Architecture of the PE file associated with the threat indicator.
1341. **`threat.enrichments.indicator.file.pe.company`**: Company name in the PE file associated with the threat indicator.
1342. **`threat.enrichments.indicator.file.pe.description`**: Description in the PE file associated with the threat indicator.
1343. **`threat.enrichments.indicator.file.pe.file_version`**: File version in the PE file associated with the threat indicator.
1344. **`threat.enrichments.indicator.file.pe.go_import_hash`**: Hash of Go imports in the PE file associated with the threat indicator.
1345. **`threat.enrichments.indicator.file.pe.go_imports`**: Go imports in the PE file associated with the threat indicator.
1346. **`threat.enrichments.indicator.file.pe.go_imports_names_entropy`**: Entropy of Go import names in the PE file associated with the threat indicator.
1347. **`threat.enrichments.indicator.file.pe.go_imports_names_var_entropy`**: Variable entropy of Go import names in the PE file associated with the threat indicator.
1348. **`threat.enrichments.indicator.file.pe.go_stripped`**: Whether Go symbols are stripped in the PE file associated with the threat indicator.
1349. **`threat.enrichments.indicator.file.pe.imphash`**: Import hash of the PE file associated with the threat indicator.
1350. **`threat.enrichments.indicator.file.pe.import_hash`**: Import hash of the PE file associated with the threat indicator.
1351. **`threat.enrichments.indicator.file.pe.imports`**: Imports in the PE file associated with the threat indicator.
1352. **`threat.enrichments.indicator.file.pe.imports_names_entropy`**: Entropy of import names in the PE file associated with the threat indicator.
1353. **`threat.enrichments.indicator.file.pe.imports_names_var_entropy`**: Variable entropy of import names in the PE file associated with the threat indicator.
1354. **`threat.enrichments.indicator.file.pe.original_file_name`**: Original file name in the PE file associated with the threat indicator.
1355. **`threat.enrichments.indicator.file.pe.pehash`**: PE hash of the file associated with the threat indicator.
1356. **`threat.enrichments.indicator.file.pe.product`**: Product name in the PE file associated with the threat indicator.
1357. **`threat.enrichments.indicator.file.pe.sections.entropy`**: Entropy of sections in the PE file associated with the threat indicator.
1358. **`threat.enrichments.indicator.file.pe.sections.name`**: Names of sections in the PE file associated with the threat indicator.
1359. **`threat.enrichments.indicator.file.pe.sections.physical_size`**: Physical size of sections in the PE file associated with the threat indicator.
1360. **`threat.enrichments.indicator.file.pe.sections.var_entropy`**: Variable entropy of sections in the PE file associated with the threat indicator.
1361. **`threat.enrichments.indicator.file.pe.sections.virtual_size`**: Virtual size of sections in the PE file associated with the threat indicator.
1362. **`threat.enrichments.indicator.file.size`**: Size of the file associated with the threat indicator.
1363. **`threat.enrichments.indicator.file.target_path`**: Target path of the file associated with the threat indicator.
1364. **`threat.enrichments.indicator.file.target_path.text`**: Text representation of the file target path associated with the threat indicator.
1365. **`threat.enrichments.indicator.file.type`**: Type of the file associated with the threat indicator.
1366. **`threat.enrichments.indicator.file.uid`**: User ID of the file owner associated with the threat indicator.
1367. **`threat.enrichments.indicator.file.x509.alternative_names`**: Alternative names in the X.509 certificate associated with the threat indicator.
1368. **`threat.enrichments.indicator.file.x509.issuer.common_name`**: Common name of the issuer in the X.509 certificate associated with the threat indicator.
1369. **`threat.enrichments.indicator.file.x509.issuer.country`**: Country of the issuer in the X.509 certificate associated with the threat indicator.
1370. **`threat.enrichments.indicator.file.x509.issuer.distinguished_name`**: Distinguished name of the issuer in the X.509 certificate associated with the threat indicator.
1371. **`threat.enrichments.indicator.file.x509.issuer.locality`**: Locality of the issuer in the X.509 certificate associated with the threat indicator.
1372. **`threat.enrichments.indicator.file.x509.issuer.organization`**: Organization of the issuer in the X.509 certificate associated with the threat indicator.
1373. **`threat.enrichments.indicator.file.x509.issuer.organizational_unit`**: Organizational unit of the issuer in the X.509 certificate associated with the threat indicator.
1374. **`threat.enrichments.indicator.file.x509.issuer.state_or_province`**: State or province of the issuer in the X.509 certificate associated with the threat indicator.
1375. **`threat.enrichments.indicator.file.x509.not_after`**: Not-after date of the X.509 certificate associated with the threat indicator.
1376. **`threat.enrichments.indicator.file.x509.not_before`**: Not-before date of the X.509 certificate associated with the threat indicator.
1377. **`threat.enrichments.indicator.file.x509.public_key_algorithm`**: Public key algorithm in the X.509 certificate associated with the threat indicator.
1378. **`threat.enrichments.indicator.file.x509.public_key_curve`**: Public key curve in the X.509 certificate associated with the threat indicator.
1379. **`threat.enrichments.indicator.file.x509.public_key_exponent`**: Public key exponent in the X.509 certificate associated with the threat indicator.
1380. **`threat.enrichments.indicator.file.x509.public_key_size`**: Public key size in the X.509 certificate associated with the threat indicator.
1381. **`threat.enrichments.indicator.file.x509.serial_number`**: Serial number of the X.509 certificate associated with the threat indicator.
1382. **`threat.enrichments.indicator.file.x509.signature_algorithm`**: Signature algorithm in the X.509 certificate associated with the threat indicator.
1383. **`threat.enrichments.indicator.file.x509.subject.common_name`**: Common name of the subject in the X.509 certificate associated with the threat indicator.
1384. **`threat.enrichments.indicator.file.x509.subject.country`**: Country of the subject in the X.509 certificate associated with the threat indicator.
1385. **`threat.enrichments.indicator.file.x509.subject.distinguished_name`**: Distinguished name of the subject in the X.509 certificate associated with the threat indicator.
1386. **`threat.enrichments.indicator.file.x509.subject.locality`**: Locality of the subject in the X.509 certificate associated with the threat indicator.
1387. **`threat.enrichments.indicator.file.x509.subject.organization`**: Organization of the subject in the X.509 certificate associated with the threat indicator.
1388. **`threat.enrichments.indicator.file.x509.subject.organizational_unit`**: Organizational unit of the subject in the X.509 certificate associated with the threat indicator.
1389. **`threat.enrichments.indicator.file.x509.subject.state_or_province`**: State or province of the subject in the X.509 certificate associated with the threat indicator.
1390. **`threat.enrichments.indicator.file.x509.version_number`**: Version number of the X.509 certificate associated with the threat indicator.
1391. **`threat.enrichments.indicator.first_seen`**: Timestamp when the threat indicator was first seen.
1392. **`threat.enrichments.indicator.geo.city_name`**: City name of the geographic location associated with the threat indicator.
1393. **`threat.enrichments.indicator.geo.continent_code`**: Continent code of the geographic location associated with the threat indicator.
1394. **`threat.enrichments.indicator.geo.continent_name`**: Continent name of the geographic location associated with the threat indicator.
1395. **`threat.enrichments.indicator.geo.country_iso_code`**: ISO code of the country associated with the threat indicator.
1396. **`threat.enrichments.indicator.geo.country_name`**: Name of the country associated with the threat indicator.
1397. **`threat.enrichments.indicator.geo.location`**: Geographic location associated with the threat indicator.
1398. **`threat.enrichments.indicator.geo.name`**: Name of the geographic location associated with the threat indicator.
1399. **`threat.enrichments.indicator.geo.postal_code`**: Postal code of the geographic location associated with the threat indicator.
1400. **`threat.enrichments.indicator.geo.region_iso_code`**: ISO code of the region associated with the threat indicator.
1401. **`threat.enrichments.indicator.geo.region_name`**: Name of the region associated with the threat indicator.
1402. **`threat.enrichments.indicator.geo.timezone`**: Time zone of the geographic location associated with the threat indicator.
1403. **`threat.enrichments.indicator.ip`**: IP address associated with the threat indicator.
1404. **`threat.enrichments.indicator.last_seen`**: Timestamp when the threat indicator was last seen.
1405. **`threat.enrichments.indicator.marking.tlp`**: Traffic Light Protocol (TLP) marking of the threat indicator.
1406. **`threat.enrichments.indicator.marking.tlp_version`**: Version of the TLP marking.
1407. **`threat.enrichments.indicator.modified_at`**: Timestamp when the threat indicator was modified.
1408. **`threat.enrichments.indicator.name`**: Name of the threat indicator.
1409. **`threat.enrichments.indicator.port`**: Port number associated with the threat indicator.
1410. **`threat.enrichments.indicator.provider`**: Provider of the threat indicator.
1411. **`threat.enrichments.indicator.reference`**: Reference associated with the threat indicator.
1412. **`threat.enrichments.indicator.registry.data.bytes`**: Byte data stored in the registry associated with the threat indicator.
1413. **`threat.enrichments.indicator.registry.data.strings`**: String data stored in the registry associated with the threat indicator.
1414. **`threat.enrichments.indicator.registry.data.type`**: Type of data stored in the registry associated with the threat indicator.
1415. **`threat.enrichments.indicator.registry.hive`**: Hive of the registry associated with the threat indicator.
1416. **`threat.enrichments.indicator.registry.key`**: Key in the registry associated with the threat indicator.
1417. **`threat.enrichments.indicator.registry.path`**: Path to the registry key associated with the threat indicator.
1418. **`threat.enrichments.indicator.registry.value`**: Value associated with the registry key.
1419. **`threat.enrichments.indicator.scanner_stats`**: Statistics from scanners associated with the threat indicator.
1420. **`threat.enrichments.indicator.sightings`**: Number of sightings of the threat indicator.
1421. **`threat.enrichments.indicator.type`**: Type of the threat indicator.
1422. **`threat.enrichments.indicator.url.domain`**: Domain of the URL associated with the threat indicator.
1423. **`threat.enrichments.indicator.url.extension`**: File extension of the URL associated with the threat indicator.
1424. **`threat.enrichments.indicator.url.fragment`**: Fragment part of the URL associated with the threat indicator.
1425. **`threat.enrichments.indicator.url.full`**: Full URL associated with the threat indicator.
1426. **`threat.enrichments.indicator.url.full.text`**: Text representation of the full URL associated with the threat indicator.
1427. **`threat.enrichments.indicator.url.original`**: Original URL associated with the threat indicator.
1428. **`threat.enrichments.indicator.url.original.text`**: Text representation of the original URL associated with the threat indicator.
1429. **`threat.enrichments.indicator.url.password`**: Password part of the URL associated with the threat indicator.
1430. **`threat.enrichments.indicator.url.path`**: Path part of the URL associated with the threat indicator.
1431. **`threat.enrichments.indicator.url.port`**: Port number of the URL associated with the threat indicator.
1432. **`threat.enrichments.indicator.url.query`**: Query part of the URL associated with the threat indicator.
1433. **`threat.enrichments.indicator.url.registered_domain`**: Registered domain of the URL associated with the threat indicator.
1434. **`threat.enrichments.indicator.url.scheme`**: Scheme of the URL associated with the threat indicator.
1435. **`threat.enrichments.indicator.url.subdomain`**: Subdomain of the URL associated with the threat indicator.
1436. **`threat.enrichments.indicator.url.top_level_domain`**: Top-level domain of the URL associated with the threat indicator.
1437. **`threat.enrichments.indicator.url.username`**: Username part of the URL associated with the threat indicator.
1438. **`threat.enrichments.indicator.x509.alternative_names`**: Alternative names in the X.509 certificate associated with the threat indicator.
1439. **`threat.enrichments.indicator.x509.issuer.common_name`**: Common name of the issuer in the X.509 certificate associated with the threat indicator.
1440. **`threat.enrichments.indicator.x509.issuer.country`**: Country of the issuer in the X.509 certificate associated with the threat indicator.
1441. **`threat.enrichments.indicator.x509.issuer.distinguished_name`**: Distinguished name of the issuer in the X.509 certificate associated with the threat indicator.
1442. **`threat.enrichments.indicator.x509.issuer.locality`**: Locality of the issuer in the X.509 certificate associated with the threat indicator.
1443. **`threat.enrichments.indicator.x509.issuer.organization`**: Organization of the issuer in the X.509 certificate associated with the threat indicator.
1444. **`threat.enrichments.indicator.x509.issuer.organizational_unit`**: Organizational unit of the issuer in the X.509 certificate associated with the threat indicator.
1445. **`threat.enrichments.indicator.x509.issuer.state_or_province`**: State or province of the issuer in the X.509 certificate associated with the threat indicator.
1446. **`threat.enrichments.indicator.x509.not_after`**: Not-after date of the X.509 certificate associated with the threat indicator.
1447. **`threat.enrichments.indicator.x509.not_before`**: Not-before date of the X.509 certificate associated with the threat indicator.
1448. **`threat.enrichments.indicator.x509.public_key_algorithm`**: Public key algorithm in the X.509 certificate associated with the threat indicator.
1449. **`threat.enrichments.indicator.x509.public_key_curve`**: Public key curve in the X.509 certificate associated with the threat indicator.
1450. **`threat.enrichments.indicator.x509.public_key_exponent`**: Public key exponent in the X.509 certificate associated with the threat indicator.
1451. **`threat.enrichments.indicator.x509.public_key_size`**: Public key size in the X.509 certificate associated with the threat indicator.
1452. **`threat.enrichments.indicator.x509.serial_number`**: Serial number of the X.509 certificate associated with the threat indicator.
1453. **`threat.enrichments.indicator.x509.signature_algorithm`**: Signature algorithm in the X.509 certificate associated with the threat indicator.
1454. **`threat.enrichments.indicator.x509.subject.common_name`**: Common name of the subject in the X.509 certificate associated with the threat indicator.
1455. **`threat.enrichments.indicator.x509.subject.country`**: Country of the subject in the X.509 certificate associated with the threat indicator.
1456. **`threat.enrichments.indicator.x509.subject.distinguished_name`**: Distinguished name of the subject in the X.509 certificate associated with the threat indicator.
1457. **`threat.enrichments.indicator.x509.subject.locality`**: Locality of the subject in the X.509 certificate associated with the threat indicator.
1458. **`threat.enrichments.indicator.x509.subject.organization`**: Organization of the subject in the X.509 certificate associated with the threat indicator.
1459. **`threat.enrichments.indicator.x509.subject.organizational_unit`**: Organizational unit of the subject in the X.509 certificate associated with the threat indicator.
1460. **`threat.enrichments.indicator.x509.subject.state_or_province`**: State or province of the subject in the X.509 certificate associated with the threat indicator.
1461. **`threat.enrichments.indicator.x509.version_number`**: Version number of the X.509 certificate associated with the threat indicator.
1462. **`threat.enrichments.matched.atomic`**: Whether the match is atomic.
1463. **`threat.enrichments.matched.field`**: Field that was matched.
1464. **`threat.enrichments.matched.id`**: ID of the matched indicator.
1465. **`threat.enrichments.matched.index`**: Index where the match was found.
1466. **`threat.enrichments.matched.occurred`**: Timestamp when the match occurred.
1467. **`threat.enrichments.matched.type`**: Type of the match.
1468. **`threat.feed.dashboard_id`**: ID of the dashboard associated with the threat feed.
1469. **`threat.feed.description`**: Description of the threat feed.
1470. **`threat.feed.name`**: Name of the threat feed.
1471. **`threat.feed.reference`**: Reference associated with the threat feed.
1472. **`threat.framework`**: Framework used for threat analysis.
1473. **`threat.group.alias`**: Alias of the threat group.
1474. **`threat.group.id`**: ID of the threat group.
1475. **`threat.group.name`**: Name of the threat group.
1476. **`threat.group.reference`**: Reference associated with the threat group.
1477. **`threat.indicator.as.number`**: Autonomous System (AS) number associated with the threat indicator.
1478. **`threat.indicator.as.organization.name`**: Name of the organization associated with the threat indicator's AS.
1479. **`threat.indicator.as.organization.name.text`**: Text representation of the threat indicator's AS organization name.
1480. **`threat.indicator.confidence`**: Confidence level of the threat indicator.
1481. **`threat.indicator.description`**: Description of the threat indicator.
1482. **`threat.indicator.email.address`**: Email address associated with the threat indicator.
1483. **`threat.indicator.file.accessed`**: Timestamp when the file associated with the threat indicator was last accessed.
1484. **`threat.indicator.file.attributes`**: Attributes of the file associated with the threat indicator.
1485. **`threat.indicator.file.code_signature.digest_algorithm`**: Algorithm used for code signing the file associated with the threat indicator.
1486. **`threat.indicator.file.code_signature.exists`**: Whether a code signature exists for the file associated with the threat indicator.
1487. **`threat.indicator.file.code_signature.signing_id`**: Signing ID of the file's code signature associated with the threat indicator.
1488. **`threat.indicator.file.code_signature.status`**: Status of the file's code signature associated with the threat indicator.
1489. **`threat.indicator.file.code_signature.subject_name`**: Subject name of the file's code signature associated with the threat indicator.
1490. **`threat.indicator.file.code_signature.team_id`**: Team ID of the file's code signature associated with the threat indicator.
1491. **`threat.indicator.file.code_signature.timestamp`**: Timestamp of the file's code signature associated with the threat indicator.
1492. **`threat.indicator.file.code_signature.trusted`**: Whether the file's code signature associated with the threat indicator is trusted.
1493. **`threat.indicator.file.code_signature.valid`**: Whether the file's code signature associated with the threat indicator is valid.
1494. **`threat.indicator.file.created`**: Timestamp when the file associated with the threat indicator was created.
1495. **`threat.indicator.file.ctime`**: Timestamp when the file's metadata was last changed.
1496. **`threat.indicator.file.device`**: Device where the file associated with the threat indicator resides.
1497. **`threat.indicator.file.directory`**: Directory of the file associated with the threat indicator.
1498. **`threat.indicator.file.drive_letter`**: Drive letter of the file associated with the threat indicator.
1499. **`threat.indicator.file.elf.architecture`**: Architecture of the ELF file associated with the threat indicator.
1500. **`threat.indicator.file.elf.byte_order`**: Byte order of the ELF file associated with the threat indicator.
1501. **`threat.indicator.file.elf.cpu_type`**: CPU type of the ELF file associated with the threat indicator.
1502. **`threat.indicator.file.elf.creation_date`**: Creation date of the ELF file associated with the threat indicator.
1503. **`threat.indicator.file.elf.exports`**: Exports in the ELF file associated with the threat indicator.
1504. **`threat.indicator.file.elf.go_import_hash`**: Hash of Go imports in the ELF file associated with the threat indicator.
1505. **`threat.indicator.file.elf.go_imports`**: Go imports in the ELF file associated with the threat indicator.
1506. **`threat.indicator.file.elf.go_imports_names_entropy`**: Entropy of Go import names in the ELF file associated with the threat indicator.
1507. **`threat.indicator.file.elf.go_imports_names_var_entropy`**: Variable entropy of Go import names in the ELF file associated with the threat indicator.
1508. **`threat.indicator.file.elf.go_stripped`**: Whether Go symbols are stripped in the ELF file associated with the threat indicator.
1509. **`threat.indicator.file.elf.header.abi_version`**: ABI version in the ELF file header associated with the threat indicator.
1510. **`threat.indicator.file.elf.header.class`**: Class in the ELF file header associated with the threat indicator.
1511. **`threat.indicator.file.elf.header.data`**: Data in the ELF file header associated with the threat indicator.
1512. **`threat.indicator.file.elf.header.entrypoint`**: Entry point in the ELF file header associated with the threat indicator.
1513. **`threat.indicator.file.elf.header.object_version`**: Object version in the ELF file header associated with the threat indicator.
1514. **`threat.indicator.file.elf.header.os_abi`**: OS ABI in the ELF file header associated with the threat indicator.
1515. **`threat.indicator.file.elf.header.type`**: Type in the ELF file header associated with the threat indicator.
1516. **`threat.indicator.file.elf.header.version`**: Version in the ELF file header associated with the threat indicator.
1517. **`threat.indicator.file.elf.import_hash`**: Import hash of the ELF file associated with the threat indicator.
1518. **`threat.indicator.file.elf.imports`**: Imports in the ELF file associated with the threat indicator.
1519. **`threat.indicator.file.elf.imports_names_entropy`**: Entropy of import names in the ELF file associated with the threat indicator.
1520. **`threat.indicator.file.elf.imports_names_var_entropy`**: Variable entropy of import names in the ELF file associated with the threat indicator.
1521. **`threat.indicator.file.elf.sections.chi2`**: Chi-squared value of sections in the ELF file associated with the threat indicator.
1522. **`threat.indicator.file.elf.sections.entropy`**: Entropy of sections in the ELF file associated with the threat indicator.
1523. **`threat.indicator.file.elf.sections.flags`**: Flags of sections in the ELF file associated with the threat indicator.
1524. **`threat.indicator.file.elf.sections.name`**: Names of sections in the ELF file associated with the threat indicator.
1525. **`threat.indicator.file.elf.sections.physical_offset`**: Physical offset of sections in the ELF file associated with the threat indicator.
1526. **`threat.indicator.file.elf.sections.physical_size`**: Physical size of sections in the ELF file associated with the threat indicator.
1527. **`threat.indicator.file.elf.sections.type`**: Type of sections in the ELF file associated with the threat indicator.
1528. **`threat.indicator.file.elf.sections.var_entropy`**: Variable entropy of sections in the ELF file associated with the threat indicator.
1529. **`threat.indicator.file.elf.sections.virtual_address`**: Virtual address of sections in the ELF file associated with the threat indicator.
1530. **`threat.indicator.file.elf.sections.virtual_size`**: Virtual size of sections in the ELF file associated with the threat indicator.
1531. **`threat.indicator.file.elf.sections.type`**: Type of sections in the ELF file associated with the threat indicator.
1532. **`threat.indicator.file.elf.sections.var_entropy`**: Variable entropy of sections in the ELF file associated with the threat indicator.
1533. **`threat.indicator.file.elf.sections.virtual_address`**: Virtual address of sections in the ELF file associated with the threat indicator.
1534. **`threat.indicator.file.elf.sections.virtual_size`**: Virtual size of sections in the ELF file associated with the threat indicator.
1535. **`threat.indicator.file.elf.segments.sections`**: Sections in ELF segments associated with the threat indicator.
1536. **`threat.indicator.file.elf.segments.type`**: Type of ELF segments associated with the threat indicator.
1537. **`threat.indicator.file.elf.shared_libraries`**: Shared libraries in the ELF file associated with the threat indicator.
1538. **`threat.indicator.file.elf.telfhash`**: Telfhash of the ELF file associated with the threat indicator.
1539. **`threat.indicator.file.extension`**: File extension of the file associated with the threat indicator.
1540. **`threat.indicator.file.fork_name`**: Name of the file fork associated with the threat indicator.
1541. **`threat.indicator.file.gid`**: Group ID of the file owner associated with the threat indicator.
1542. **`threat.indicator.file.group`**: Group name of the file owner associated with the threat indicator.
1543. **`threat.indicator.file.hash.md5`**: MD5 hash of the file associated with the threat indicator.
1544. **`threat.indicator.file.hash.sha1`**: SHA-1 hash of the file associated with the threat indicator.
1545. **`threat.indicator.file.hash.sha256`**: SHA-256 hash of the file associated with the threat indicator.
1546. **`threat.indicator.file.hash.sha384`**: SHA-384 hash of the file associated with the threat indicator.
1547. **`threat.indicator.file.hash.sha512`**: SHA-512 hash of the file associated with the threat indicator.
1548. **`threat.indicator.file.hash.ssdeep`**: ssdeep hash of the file associated with the threat indicator.
1549. **`threat.indicator.file.hash.tlsh`**: tlsh hash of the file associated with the threat indicator.
1550. **`threat.indicator.file.inode`**: Inode number of the file associated with the threat indicator.
1551. **`threat.indicator.file.mime_type`**: MIME type of the file associated with the threat indicator.
1552. **`threat.indicator.file.mode`**: File mode (permissions) of the file associated with the threat indicator.
1553. **`threat.indicator.file.mtime`**: Timestamp when the file's contents were last modified.
1554. **`threat.indicator.file.name`**: Name of the file associated with the threat indicator.
1555. **`threat.indicator.file.owner`**: Owner of the file associated with the threat indicator.
1556. **`threat.indicator.file.path`**: Path to the file associated with the threat indicator.
1557. **`threat.indicator.file.path.text`**: Text representation of the file path associated with the threat indicator.
1558. **`threat.indicator.file.pe.architecture`**: Architecture of the PE file associated with the threat indicator.
1559. **`threat.indicator.file.pe.company`**: Company name in the PE file associated with the threat indicator.
1560. **`threat.indicator.file.pe.description`**: Description in the PE file associated with the threat indicator.
1561. **`threat.indicator.file.pe.file_version`**: File version in the PE file associated with the threat indicator.
1562. **`threat.indicator.file.pe.go_import_hash`**: Hash of Go imports in the PE file associated with the threat indicator.
1563. **`threat.indicator.file.pe.go_imports`**: Go imports in the PE file associated with the threat indicator.
1564. **`threat.indicator.file.pe.go_imports_names_entropy`**: Entropy of Go import names in the PE file associated with the threat indicator.
1565. **`threat.indicator.file.pe.go_imports_names_var_entropy`**: Variable entropy of Go import names in the PE file associated with the threat indicator.
1566. **`threat.indicator.file.pe.go_stripped`**: Whether Go symbols are stripped in the PE file associated with the threat indicator.
1567. **`threat.indicator.file.pe.imphash`**: Import hash of the PE file associated with the threat indicator.
1568. **`threat.indicator.file.pe.import_hash`**: Import hash of the PE file associated with the threat indicator.
1569. **`threat.indicator.file.pe.imports`**: Imports in the PE file associated with the threat indicator.
1570. **`threat.indicator.file.pe.imports_names_entropy`**: Entropy of import names in the PE file associated with the threat indicator.
1571. **`threat.indicator.file.pe.imports_names_var_entropy`**: Variable entropy of import names in the PE file associated with the threat indicator.
1572. **`threat.indicator.file.pe.original_file_name`**: Original file name in the PE file associated with the threat indicator.
1573. **`threat.indicator.file.pe.pehash`**: PE hash of the file associated with the threat indicator.
1574. **`threat.indicator.file.pe.product`**: Product name in the PE file associated with the threat indicator.
1575. **`threat.indicator.file.pe.sections.entropy`**: Entropy of sections in the PE file associated with the threat indicator.
1576. **`threat.indicator.file.pe.sections.name`**: Names of sections in the PE file associated with the threat indicator.
1577. **`threat.indicator.file.pe.sections.physical_size`**: Physical size of sections in the PE file associated with the threat indicator.
1578. **`threat.indicator.file.pe.sections.var_entropy`**: Variable entropy of sections in the PE file associated with the threat indicator.
1579. **`threat.indicator.file.pe.sections.virtual_size`**: Virtual size of sections in the PE file associated with the threat indicator.
1580. **`threat.indicator.file.size`**: Size of the file associated with the threat indicator.
1581. **`threat.indicator.file.target_path`**: Target path of the file associated with the threat indicator.
1582. **`threat.indicator.file.target_path.text`**: Text representation of the file target path associated with the threat indicator.
1583. **`threat.indicator.file.type`**: Type of the file associated with the threat indicator.
1584. **`threat.indicator.file.uid`**: User ID of the file owner associated with the threat indicator.
1585. **`threat.indicator.file.x509.alternative_names`**: Alternative names in the X.509 certificate associated with the threat indicator.
1586. **`threat.indicator.file.x509.issuer.common_name`**: Common name of the issuer in the X.509 certificate associated with the threat indicator.
1587. **`threat.indicator.file.x509.issuer.country`**: Country of the issuer in the X.509 certificate associated with the threat indicator.
1588. **`threat.indicator.file.x509.issuer.distinguished_name`**: Distinguished name of the issuer in the X.509 certificate associated with the threat indicator.
1589. **`threat.indicator.file.x509.issuer.locality`**: Locality of the issuer in the X.509 certificate associated with the threat indicator.
1590. **`threat.indicator.file.x509.issuer.organization`**: Organization of the issuer in the X.509 certificate associated with the threat indicator.
1591. **`threat.indicator.file.x509.issuer.organizational_unit`**: Organizational unit of the issuer in the X.509 certificate associated with the threat indicator.
1592. **`threat.indicator.file.x509.issuer.state_or_province`**: State or province of the issuer in the X.509 certificate associated with the threat indicator.
1593. **`threat.indicator.file.x509.not_after`**: Not-after date of the X.509 certificate associated with the threat indicator.
1594. **`threat.indicator.file.x509.not_before`**: Not-before date of the X.509 certificate associated with the threat indicator.
1595. **`threat.indicator.file.x509.public_key_algorithm`**: Public key algorithm in the X.509 certificate associated with the threat indicator.
1596. **`threat.indicator.file.x509.public_key_curve`**: Public key curve in the X.509 certificate associated with the threat indicator.
1597. **`threat.indicator.file.x509.public_key_exponent`**: Public key exponent in the X.509 certificate associated with the threat indicator.
1598. **`threat.indicator.file.x509.public_key_size`**: Public key size in the X.509 certificate associated with the threat indicator.
1599. **`threat.indicator.file.x509.serial_number`**: Serial number of the X.509 certificate associated with the threat indicator.
1600. **`threat.indicator.file.x509.signature_algorithm`**: Signature algorithm in the X.509 certificate associated with the threat indicator.
1601. **`threat.indicator.file.x509.subject.common_name`**: Common name of the subject in the X.509 certificate associated with the threat indicator.
1602. **`threat.indicator.file.x509.subject.country`**: Country of the subject in the X.509 certificate associated with the threat indicator.
1603. **`threat.indicator.file.x509.subject.distinguished_name`**: Distinguished name of the subject in the X.509 certificate associated with the threat indicator.
1604. **`threat.indicator.file.x509.subject.locality`**: Locality of the subject in the X.509 certificate associated with the threat indicator.
1605. **`threat.indicator.file.x509.subject.organization`**: Organization of the subject in the X.509 certificate associated with the threat indicator.
1606. **`threat.indicator.file.x509.subject.organizational_unit`**: Organizational unit of the subject in the X.509 certificate associated with the threat indicator.
1607. **`threat.indicator.file.x509.subject.state_or_province`**: State or province of the subject in the X.509 certificate associated with the threat indicator.
1608. **`threat.indicator.file.x509.version_number`**: Version number of the X.509 certificate associated with the threat indicator.
1609. **`threat.indicator.first_seen`**: Timestamp when the threat indicator was first seen.
1610. **`threat.indicator.geo.city_name`**: City name of the geographic location associated with the threat indicator.
1611. **`threat.indicator.geo.continent_code`**: Continent code of the geographic location associated with the threat indicator.
1612. **`threat.indicator.geo.continent_name`**: Continent name of the geographic location associated with the threat indicator.
1613. **`threat.indicator.geo.country_iso_code`**: ISO code of the country associated with the threat indicator.
1614. **`threat.indicator.geo.country_name`**: Name of the country associated with the threat indicator.
1615. **`threat.indicator.geo.location`**: Geographic location associated with the threat indicator.
1616. **`threat.indicator.geo.name`**: Name of the geographic location associated with the threat indicator.
1617. **`threat.indicator.geo.postal_code`**: Postal code of the geographic location associated with the threat indicator.
1618. **`threat.indicator.geo.region_iso_code`**: ISO code of the region associated with the threat indicator.
1619. **`threat.indicator.geo.region_name`**: Name of the region associated with the threat indicator.
1620. **`threat.indicator.geo.timezone`**: Time zone of the geographic location associated with the threat indicator.
1621. **`threat.indicator.ip`**: IP address associated with the threat indicator.
1622. **`threat.indicator.last_seen`**: Timestamp when the threat indicator was last seen.
1623. **`threat.indicator.marking.tlp`**: Traffic Light Protocol (TLP) marking of the threat indicator.
1624. **`threat.indicator.marking.tlp_version`**: Version of the TLP marking.
1625. **`threat.indicator.modified_at`**: Timestamp when the threat indicator was modified.
1626. **`threat.indicator.name`**: Name of the threat indicator.
1627. **`threat.indicator.port`**: Port number associated with the threat indicator.
1628. **`threat.indicator.provider`**: Provider of the threat indicator.
1629. **`threat.indicator.reference`**: Reference associated with the threat indicator.
1630. **`threat.indicator.registry.data.bytes`**: Byte data stored in the registry associated with the threat indicator.
1631. **`threat.indicator.registry.data.strings`**: String data stored in the registry associated with the threat indicator.
1632. **`threat.indicator.registry.data.type`**: Type of data stored in the registry associated with the threat indicator.
1633. **`threat.indicator.registry.hive`**: Hive of the registry associated with the threat indicator.
1634. **`threat.indicator.registry.key`**: Key in the registry associated with the threat indicator.
1635. **`threat.indicator.registry.path`**: Path to the registry key associated with the threat indicator.
1636. **`threat.indicator.registry.value`**: Value associated with the registry key.
1637. **`threat.indicator.scanner_stats`**: Statistics from scanners associated with the threat indicator.
1638. **`threat.indicator.sightings`**: Number of sightings of the threat indicator.
1639. **`threat.indicator.type`**: Type of the threat indicator.
1640. **`threat.indicator.url.domain`**: Domain of the URL associated with the threat indicator.
1641. **`threat.indicator.url.extension`**: File extension of the URL associated with the threat indicator.
1642. **`threat.indicator.url.fragment`**: Fragment part of the URL associated with the threat indicator.
1643. **`threat.indicator.url.full`**: Full URL associated with the threat indicator.
1644. **`threat.indicator.url.full.text`**: Text representation of the full URL associated with the threat indicator.
1645. **`threat.indicator.url.original`**: Original URL associated with the threat indicator.
1646. **`threat.indicator.url.original.text`**: Text representation of the original URL associated with the threat indicator.
1647. **`threat.indicator.url.password`**: Password part of the URL associated with the threat indicator.
1648. **`threat.indicator.url.path`**: Path part of the URL associated with the threat indicator.
1649. **`threat.indicator.url.port`**: Port number of the URL associated with the threat indicator.
1650. **`threat.indicator.url.query`**: Query part of the URL associated with the threat indicator.
1651. **`threat.indicator.url.registered_domain`**: Registered domain of the URL associated with the threat indicator.
1652. **`threat.indicator.url.scheme`**: Scheme of the URL associated with the threat indicator.
1653. **`threat.indicator.url.subdomain`**: Subdomain of the URL associated with the threat indicator.
1654. **`threat.indicator.url.top_level_domain`**: Top-level domain of the URL associated with the threat indicator.
1655. **`threat.indicator.url.username`**: Username part of the URL associated with the threat indicator.
1656. **`threat.indicator.x509.alternative_names`**: Alternative names in the X.509 certificate associated with the threat indicator.
1657. **`threat.indicator.x509.issuer.common_name`**: Common name of the issuer in the X.509 certificate associated with the threat indicator.
1658. **`threat.indicator.x509.issuer.country`**: Country of the issuer in the X.509 certificate associated with the threat indicator.
1659. **`threat.indicator.x509.issuer.distinguished_name`**: Distinguished name of the issuer in the X.509 certificate associated with the threat indicator.
1660. **`threat.indicator.x509.issuer.locality`**: Locality of the issuer in the X.509 certificate associated with the threat indicator.
1661. **`threat.indicator.x509.issuer.organization`**: Organization of the issuer in the X.509 certificate associated with the threat indicator.
1662. **`threat.indicator.x509.issuer.organizational_unit`**: Organizational unit of the issuer in the X.509 certificate associated with the threat indicator.
1663. **`threat.indicator.x509.issuer.state_or_province`**: State or province of the issuer in the X.509 certificate associated with the threat indicator.
1664. **`threat.indicator.x509.not_after`**: Not-after date of the X.509 certificate associated with the threat indicator.
1665. **`threat.indicator.x509.not_before`**: Not-before date of the X.509 certificate associated with the threat indicator.
1666. **`threat.indicator.x509.public_key_algorithm`**: Public key algorithm in the X.509 certificate associated with the threat indicator.
1667. **`threat.indicator.x509.public_key_curve`**: Public key curve in the X.509 certificate associated with the threat indicator.
1668. **`threat.indicator.file.elf.sections.type`**: This field refers to the type of sections in the ELF file, which could include code, data, or other types.
1669. **`threat.indicator.file.elf.sections.var_entropy`**: This measures the variable entropy of sections, which can indicate how complex or obfuscated the code is.
1670. **`threat.indicator.file.elf.sections.virtual_address`**: The virtual address where a section is loaded in memory.
1671. **`threat.indicator.file.elf.sections.virtual_size`**: The size of a section in virtual memory.
1672. **`threat.indicator.file.elf.segments.sections`**: Sections included in each segment.
1673. **`threat.indicator.file.elf.segments.type`**: Type of segments, such as `PT_LOAD` for loading code and data
1674. **`threat.indicator.x509.public_key_exponent`**: Exponent used in the public key algorithm of the X.509 certificate associated with the threat indicator.
1675. **`threat.indicator.x509.public_key_size`**: Size of the public key space in bits for the X.509 certificate associated with the threat indicator.
1676. **`threat.indicator.x509.serial_number`**: Serial number of the X.509 certificate associated with the threat indicator, used to distinguish it from other certificates.
1677. **`threat.indicator.x509.signature_algorithm`**: Algorithm used to sign the X.509 certificate associated with the threat indicator.
1678. **`threat.indicator.x509.subject.common_name`**: Common name of the subject in the X.509 certificate associated with the threat indicator.
1679. **`threat.indicator.x509.subject.country`**: Country of the subject in the X.509 certificate associated with the threat indicator.
1680. **`threat.indicator.x509.subject.distinguished_name`**: Distinguished name of the subject in the X.509 certificate associated with the threat indicator.
1681. **`threat.indicator.x509.subject.locality`**: Locality of the subject in the X.509 certificate associated with the threat indicator.
1682. **`threat.indicator.x509.subject.organization`**: Organization of the subject in the X.509 certificate associated with the threat indicator.
1683. **`threat.indicator.x509.subject.organizational_unit`**: Organizational unit of the subject in the X.509 certificate associated with the threat indicator.
1684. **`threat.indicator.x509.subject.state_or_province`**: State or province of the subject in the X.509 certificate associated with the threat indicator.
1685. **`threat.indicator.x509.version_number`**: Version number of the X.509 certificate associated with the threat indicator.
1686. **`threat.software.alias`**: Alias of the software associated with the threat.
1687. **`threat.software.id`**: ID of the software associated with the threat.
1688. **`threat.software.name`**: Name of the software associated with the threat.
1689. **`threat.software.platforms`**: Platforms supported by the software associated with the threat.
1690. **`threat.software.reference`**: Reference associated with the software.
1691. **`threat.software.type`**: Type of the software associated with the threat.
1692. **`threat.tactic.id`**: ID of the threat tactic.
1693. **`threat.tactic.name`**: Name of the threat tactic.
1694. **`threat.tactic.reference`**: Reference for the threat tactic.
1695. **`threat.technique.id`**: ID of the threat technique.
1696. **`threat.technique.name`**: Name of the threat technique.
1697. **`threat.technique.name.text`**: Text representation of the threat technique name.
1698. **`threat.technique.reference`**: Reference for the threat technique.
1699. **`threat.technique.subtechnique.id`**: ID of the threat subtechnique.
1700. **`threat.technique.subtechnique.name`**: Name of the threat subtechnique.
1701. **`threat.technique.subtechnique.name.text`**: Text representation of the threat subtechnique name.
1702. **`threat.technique.subtechnique.reference`**: Reference for the threat subtechnique.
1703. **`Time`**: This field seems to be a placeholder or category; more context is needed.
1704. **`@timestamp`**: Timestamp when the event occurred.
1705. **`tls.cipher`**: Cipher used in the TLS connection.
1706. **`tls.client.certificate`**: Client's TLS certificate.
1707. **`tls.client.certificate_chain`**: Chain of certificates presented by the client.
1708. **`tls.client.hash.md5`**: MD5 hash of the client's TLS certificate.
1709. **`tls.client.hash.sha1`**: SHA-1 hash of the client's TLS certificate.
1710. **`tls.client.hash.sha256`**: SHA-256 hash of the client's TLS certificate.
1711. **`tls.client.issuer`**: Issuer of the client's TLS certificate.
1712. **`tls.client.ja3`**: JA3 fingerprint of the client's TLS connection.
1713. **`tls.client.not_after`**: Not-after date of the client's TLS certificate.
1714. **`tls.client.not_before`**: Not-before date of the client's TLS certificate.
1715. **`tls.client.server_name`**: Server name indicated by the client in the TLS connection.
1716. **`tls.client.subject`**: Subject of the client's TLS certificate.
1717. **`tls.client.supported_ciphers`**: Ciphers supported by the client.
1718. **`tls.client.x509.alternative_names`**: Alternative names in the client's X.509 certificate.
1719. **`tls.client.x509.issuer.common_name`**: Common name of the issuer in the client's X.509 certificate.
1720. **`tls.client.x509.issuer.country`**: Country of the issuer in the client's X.509 certificate.
1721. **`tls.client.x509.issuer.distinguished_name`**: Distinguished name of the issuer in the client's X.509 certificate.
1722. **`tls.client.x509.issuer.locality`**: Locality of the issuer in the client's X.509 certificate.
1723. **`tls.client.x509.issuer.organization`**: Organization of the issuer in the client's X.509 certificate.
1724. **`tls.client.x509.issuer.organizational_unit`**: Organizational unit of the issuer in the client's X.509 certificate.
1725. **`tls.client.x509.issuer.state_or_province`**: State or province of the issuer in the client's X.509 certificate.
1726. **`tls.client.x509.not_after`**: Not-after date of the client's X.509 certificate.
1727. **`tls.client.x509.not_before`**: Not-before date of the client's X.509 certificate.
1728. **`tls.client.x509.public_key_algorithm`**: Public key algorithm used in the client's X.509 certificate.
1729. **`tls.client.x509.public_key_curve`**: Public key curve used in the client's X.509 certificate.
1730. **`tls.client.x509.public_key_exponent`**: Public key exponent used in the client's X.509 certificate.
1731. **`tls.client.x509.public_key_size`**: Size of the public key space in the client's X.509 certificate.
1732. **`tls.client.x509.serial_number`**: Serial number of the client's X.509 certificate.
1733. **`tls.client.x509.signature_algorithm`**: Signature algorithm used in the client's X.509 certificate.
1734. **`tls.client.x509.subject.common_name`**: Common name of the subject in the client's X.509 certificate.
1735. **`tls.client.x509.subject.country`**: Country of the subject in the client's X.509 certificate.
1736. **`tls.client.x509.subject.distinguished_name`**: Distinguished name of the subject in the client's X.509 certificate.
1737. **`tls.client.x509.subject.locality`**: Locality of the subject in the client's X.509 certificate.
1738. **`tls.client.x509.subject.organization`**: Organization of the subject in the client's X.509 certificate.
1739. **`tls.client.x509.subject.organizational_unit`**: Organizational unit of the subject in the client's X.509 certificate.
1740. **`tls.client.x509.subject.state_or_province`**: State or province of the subject in the client's X.509 certificate.
1741. **`tls.client.x509.version_number`**: Version number of the client's X.509 certificate.
1742. **`tls.curve`**: Elliptic curve used in the TLS connection.
1743. **`tls.established`**: Whether the TLS connection was established.
1744. **`tls.next_protocol`**: Next protocol negotiated in the TLS connection.
1745. **`tls.resumed`**: Whether the TLS connection was resumed.
1746. **`tls.server.certificate`**: Server's TLS certificate.
1747. **`tls.server.certificate_chain`**: Chain of certificates presented by the server.
1748. **`tls.server.hash.md5`**: MD5 hash of the server's TLS certificate.
1749. **`tls.server.hash.sha1`**: SHA-1 hash of the server's TLS certificate.
1750. **`tls.server.hash.sha256`**: SHA-256 hash of the server's TLS certificate.
1751. **`tls.server.issuer`**: Issuer of the server's TLS certificate.
1752. **`tls.server.ja3s`**: JA3S fingerprint of the server's TLS connection.
1753. **`tls.server.not_after`**: Not-after date of the server's TLS certificate.
1754. **`tls.server.not_before`**: Not-before date of the server's TLS certificate.
1755. **`tls.server.subject`**: Subject of the server's TLS certificate.
1756. **`tls.server.x509.alternative_names`**: Alternative names in the server's X.509 certificate.
1757. **`tls.server.x509.issuer.common_name`**: Common name of the issuer in the server's X.509 certificate.
1758. **`tls.server.x509.issuer.country`**: Country of the issuer in the server's X.509 certificate.
1759. **`tls.server.x509.issuer.distinguished_name`**: Distinguished name of the issuer in the server's X.509 certificate.
1760. **`tls.server.x509.issuer.locality`**: Locality of the issuer in the server's X.509 certificate.
1761. **`tls.server.x509.issuer.organization`**: Organization of the issuer in the server's X.509 certificate.
1762. **`tls.server.x509.issuer.organizational_unit`**: Organizational unit of the issuer in the server's X.509 certificate.
1763. **`tls.server.x509.issuer.state_or_province`**: State or province of the issuer in the server's X.509 certificate.
1764. **`tls.server.x509.not_after`**: Not-after date of the server's X.509 certificate.
1765. **`tls.server.x509.not_before`**: Not-before date of the server's X.509 certificate.
1766. **`tls.server.x509.public_key_algorithm`**: Public key algorithm used in the server's X.509 certificate.
1767. **`tls.server.x509.public_key_curve`**: Public key curve used in the server's X.509 certificate.
1768. **`tls.server.x509.public_key_exponent`**: Public key exponent used in the server's X.509 certificate.
1769. **`tls.server.x509.public_key_size`**: Size of the public key space in the server's X.509 certificate.
1770. **`tls.server.x509.serial_number`**: Serial number of the server's X.509 certificate.
1771. **`tls.server.x509.signature_algorithm`**: Signature algorithm used in the server's X.509 certificate.
1772. **`tls.server.x509.subject.common_name`**: Common name of the subject in the server's X.509 certificate.
1773. **`tls.server.x509.subject.country`**: Country of the subject in the server's X.509 certificate.
1774. **`tls.server.x509.subject.distinguished_name`**: Distinguished name of the subject in the server's X.509 certificate.
1775. **`tls.server.x509.subject.locality`**: Locality of the subject in the server's X.509 certificate.
1776. **`tls.server.x509.subject.organization`**: Organization of the subject in the server's X.509 certificate.
1777. **`tls.server.x509.subject.organizational_unit`**: Organizational unit of the subject in the server's X.509 certificate.
1778. **`tls.server.x509.subject.state_or_province`**: State or province of the subject in the server's X.509 certificate.
1779. **`tls.server.x509.version_number`**: Version number of the server's X.509 certificate.
1780. **`tls.version`**: Version of the TLS protocol used.
1781. **`tls.version_protocol`**: Version of the protocol negotiated in the TLS connection.
1782. **`trace.id`**: ID of the trace.
1783. **`transaction.id`**: ID of the transaction.
1784. **`unit.id`**: ID of the unit.
1785. **`unit.old_state`**: Previous state of the unit.
1786. **`unit.state`**: Current state of the unit.
1787. **`unit.type`**: Type of the unit.
1788. **`url.domain`**: Domain of the URL.
1789. **`url.extension`**: File extension of the URL.
1790. **`url.fragment`**: Fragment part of the URL.
1791. **`url.full`**: Full URL.
1792. **`url.full.text`**: Text representation of the full URL.
1793. **`url.original`**: Original URL.
1794. **`url.original.text`**: Text representation of the original URL.
1795. **`url.password`**: Password part of the URL.
1796. **`url.path`**: Path part of the URL.
1797. **`url.port`**: Port number of the URL.
1798. **`url.query`**: Query part of the URL.
1799. **`url.registered_domain`**: Registered domain of the URL.
1800. **`url.scheme`**: Scheme of the URL.
1801. **`url.subdomain`**: Subdomain of the URL.
1802. **`url.top_level_domain`**: Top-level domain of the URL.
1803. **`url.username`**: Username part of the URL.
1804. **`user_agent.device.name`**: Name of the device used by the user agent.
1805. **`user_agent.name`**: Name of the user agent.
1806. **`user_agent.original`**: Original user agent string.
1807. **`user_agent.original.text`**: Text representation of the original user agent.
1808. **`user_agent.os.family`**: Family of the operating system used by the user agent.
1809. **`user_agent.os.full`**: Full name of the operating system used by the user agent.
1810. **`user_agent.os.full.text`**: Text representation of the full OS name used by the user agent.
1811. **`user_agent.os.kernel`**: Kernel version of the operating system used by the user agent.
1812. **`user_agent.os.name`**: Name of the operating system used by the user agent.
1813. **`user_agent.os.name.text`**: Text representation of the OS name used by the user agent.
1814. **`user_agent.os.platform`**: Platform of the operating system used by the user agent.
1815. **`user_agent.os.type`**: Type of the operating system used by the user agent.
1816. **`user_agent.os.version`**: Version of the operating system used by the user agent.
1817. **`user_agent.version`**: Version of the user agent.
1818. **`user.asset.criticality`**: Criticality of the user's asset.
1819. **`user.changes.domain`**: Domain of the user who made changes.
1820. **`user.changes.email`**: Email address of the user who made changes.
1821. **`user.changes.full_name`**: Full name of the user who made changes.
1822. **`user.changes.full_name.text`**: Text representation of the full name of the user who made changes.
1823. **`user.changes.group.domain`**: Domain of the group of the user who made changes.
1824. **`user.changes.group.id`**: ID of the group of the user who made changes.
1825. **`user.changes.group.name`**: Name of the group of the user who made changes.
1826. **`user.changes.hash`**: Hash of the user who made changes.
1827. **`user.changes.id`**: ID of the user who made changes.
1828. **`user.changes.name`**: Name of the user who made changes.
1829. **`user.changes.name.text`**: Text representation of the name of the user who made changes.
1830. **`user.changes.roles`**: Roles of the user who made changes.
1831. **`user.domain`**: Domain of the user.
1832. **`user.effective.domain`**: Effective domain of the user.
1833. **`user.effective.email`**: Effective email address of the user.
1834. **`user.effective.full_name`**: Effective full name of the user.
1835. **`user.effective.full_name.text`**: Text representation of the effective full name of the user.
1836. **`user.effective.group.domain`**: Effective domain of the user's group.
1837. **`user.effective.group.id`**: Effective ID of the user's group.
1838. **`user.effective.group.name`**: Effective name of the user's group.
1839. **`user.effective.hash`**: Effective hash of the user.
1840. **`user.effective.id`**: Effective ID of the user.
1841. **`user.effective.name`**: Effective name of the user.
1842. **`user.effective.name.text`**: Text representation of the effective name of the user.
1843. **`user.effective.roles`**: Effective roles of the user.
1844. **`user.email`**: Email address of the user.
1845. **`user.full_name`**: Full name of the user.
1846. **`user.full_name.text`**: Text representation of the user's full name.
1847. **`user.group.domain`**: Domain of the user's group.
1848. **`user.group.id`**: ID of the user's group.
1849. **`user.group.name`**: Name of the user's group.
1850. **`user.hash`**: Hash of the user's credentials.
1851. **`user.id`**: ID of the user.
1852. **`user.name`**: Name of the user.
1853. **`user.name.text`**: Text representation of the user's name.
1854. **`user.risk.calculated_level`**: Calculated risk level of the user.
1855. **`user.risk.calculated_score`**: Calculated risk score of the user.
1856. **`user.risk.calculated_score_norm`**: Normalized calculated risk score of the user.
1857. **`user.risk.static_level`**: Static risk level of the user.
1858. **`user.risk.static_score`**: Static risk score of the user.
1859. **`user.risk.static_score_norm`**: Normalized static risk score of the user.
1860. **`user.roles`**: Roles of the user.
1861. **`user.target.domain`**: Domain of the target user.
1862. **`user.target.email`**: Email address of the target user.
1863. **`user.target.full_name`**: Full name of the target user.
1864. **`user
1865. **`winlog.event_data.AccessGranted`**: Whether access was granted.
1866. **`winlog.event_data.AccessList`**: List of accesses granted or denied.
1867. **`winlog.event_data.AccessListDescription`**: Description of the access list.
1868. **`winlog.event_data.AccessMask`**: Bitmask representing the access rights.
1869. **`winlog.event_data.AccessMaskDescription`**: Description of the access mask.
1870. **`winlog.event_data.AccessReason`**: Reason for granting or denying access.
1871. **`winlog.event_data.AccessRemoved`**: Whether access was removed.
1872. **`winlog.event_data.AccountDomain`**: Domain of the account involved.
1873. **`winlog.event_data.AccountExpires`**: Timestamp when the account expires.
1874. **`winlog.event_data.AccountName`**: Name of the account involved.
1875. **`winlog.event_data.Address`**: Address associated with the event.
1876. **`winlog.event_data.AddressLength`**: Length of the address.
1877. **`winlog.event_data.AdvancedOptions`**: Advanced options used in the event.
1878. **`winlog.event_data.AlgorithmName`**: Name of the algorithm used.
1879. **`winlog.event_data.AllowedToDelegateTo`**: Accounts to which delegation is allowed.
1880. **`winlog.event_data.Application`**: Application involved in the event.
1881. **`winlog.event_data.AttributeValue`**: Value of an attribute.
1882. **`winlog.event_data.AuditPolicyChanges`**: Changes made to audit policies.
1883. **`winlog.event_data.AuditPolicyChangesDescription`**: Description of audit policy changes.
1884. **`winlog.event_data.AuditSourceName`**: Name of the audit source.
1885. **`winlog.event_data.AuthenticationPackageName`**: Name of the authentication package used.
1886. **`winlog.event_data.Binary`**: Binary data associated with the event.
1887. **`winlog.event_data.BitlockerUserInputTime`**: Timestamp when BitLocker user input occurred.
1888. **`winlog.event_data.BootId`**: ID of the boot process.
1889. **`winlog.event_data.BootMenuPolicy`**: Policy for the boot menu.
1890. **`winlog.event_data.BootMode`**: Mode in which the system booted.
1891. **`winlog.event_data.BootStatusPolicy`**: Policy for boot status.
1892. **`winlog.event_data.BootType`**: Type of boot (e.g., normal, safe mode).
1893. **`winlog.event_data.BuildVersion`**: Version of the build.
1894. **`winlog.event_data.CallerProcessId`**: ID of the calling process.
1895. **`winlog.event_data.CallerProcessImageName`**: Image name of the calling process.
1896. **`winlog.event_data.CallerProcessName`**: Name of the calling process.
1897. **`winlog.event_data.CallTrace`**: Call trace information.
1898. **`winlog.event_data.Category`**: Category of the event.
1899. **`winlog.event_data.CategoryId`**: ID of the event category.
1900. **`winlog.event_data.ClientAddress`**: Address of the client.
1901. **`winlog.event_data.ClientCreationTime`**: Timestamp when the client was created.
1902. **`winlog.event_data.ClientName`**: Name of the client.
1903. **`winlog.event_data.ClientProcessId`**: ID of the client process.
1904. **`winlog.event_data.CommandLine`**: Command line used to start the process.
1905. **`winlog.event_data.Company`**: Company name associated with the event.
1906. **`winlog.event_data.ComputerAccountChange`**: Change made to a computer account.
1907. **`winlog.event_data.Config`**: Configuration associated with the event.
1908. **`winlog.event_data.ConfigAccessPolicy`**: Policy for accessing configuration.
1909. **`winlog.event_data.Configuration`**: Configuration details.
1910. **`winlog.event_data.ConfigurationFileHash`**: Hash of the configuration file.
1911. **`winlog.event_data.CorruptionActionState`**: State of corruption action.
1912. **`winlog.event_data.CountNew`**: Count of new items.
1913. **`winlog.event_data.CountOfCredentialsReturned`**: Number of credentials returned.
1914. **`winlog.event_data.CountOld`**: Count of old items.
1915. **`winlog.event_data.CrashOnAuditFailValue`**: Value indicating whether to crash on audit failure.
1916. **`winlog.event_data.CreationUtcTime`**: Timestamp when the event was created in UTC.
1917. **`winlog.event_data.CurrentBias`**: Current bias of the system clock.
1918. **`winlog.event_data.CurrentDirectory`**: Current working directory.
1919. **`winlog.event_data.CurrentProfile`**: Current profile being used.
1920. **`winlog.event_data.CurrentStratumNumber`**: Current stratum number of the NTP server.
1921. **`winlog.event_data.CurrentTimeZoneID`**: ID of the current time zone.
1922. **`winlog.event_data.Default`**: Default value or setting.
1923. **`winlog.event_data.Description`**: Description of the event.
1924. **`winlog.event_data.DestAddress`**: Destination address.
1925. **`winlog.event_data.DestinationHostname`**: Hostname of the destination.
1926. **`winlog.event_data.DestinationIp`**: IP address of the destination.
1927. **`winlog.event_data.DestinationIsIpv6`**: Whether the destination IP is IPv6.
1928. **`winlog.event_data.DestinationPort`**: Port number of the destination.
1929. **`winlog.event_data.DestinationPortName`**: Name of the destination port.
1930. **`winlog.event_data.DestPort`**: Destination port number.
1931. **`winlog.event_data.Detail`**: Detailed information about the event.
1932. **`winlog.event_data.Details`**: Additional details about the event.
1933. **`winlog.event_data.DeviceName`**: Name of the device involved.
1934. **`winlog.event_data.DeviceNameLength`**: Length of the device name.
1935. **`winlog.event_data.DeviceTime`**: Timestamp from the device.
1936. **`winlog.event_data.DeviceVersionMajor`**: Major version of the device.
1937. **`winlog.event_data.DeviceVersionMinor`**: Minor version of the device.
1938. **`winlog.event_data.Direction`**: Direction of the event (e.g., incoming, outgoing).
1939. **`winlog.event_data.DirtyPages`**: Number of dirty pages.
1940. **`winlog.event_data.DisableIntegrityChecks`**: Whether integrity checks are disabled.
1941. **`winlog.event_data.DisplayName`**: Display name of the object involved.
1942. **`winlog.event_data.DnsHostName`**: DNS hostname of the system.
1943. **`winlog.event_data.DomainBehaviorVersion`**: Version of domain behavior.
1944. **`winlog.event_data.DomainName`**: Name of the domain.
1945. **`winlog.event_data.DomainPeer`**: Peer domain involved.
1946. **`winlog.event_data.DomainPolicyChanged`**: Change made to domain policy.
1947. **`winlog.event_data.DomainSid`**: SID of the domain.
1948. **`winlog.event_data.DriveName`**: Name of the drive involved.
1949. **`winlog.event_data.DriverName`**: Name of the driver involved.
1950. **`winlog.event_data.DriverNameLength`**: Length of the driver name.
1951. **`winlog.event_data.Dummy`**: Placeholder or dummy value.
1952. **`winlog.event_data.DwordVal`**: DWORD value associated with the event.
1953. **`winlog.event_data.EfiDaylightFlags`**: EFI daylight flags.
1954. **`winlog.event_data.EfiTime`**: EFI time.
1955. **`winlog.event_data.EfiTimeZoneBias`**: EFI time zone bias.
1956. **`winlog.event_data.ElevatedToken`**: Whether an elevated token was used.
1957. **`winlog.event_data.EnableDisableReason`**: Reason for enabling or disabling.
1958. **`winlog.event_data.EnabledNew`**: Whether a new setting is enabled.
1959. **`winlog.event_data.EnabledPrivilegeList`**: List of enabled privileges.
1960. **`winlog.event_data.EntryCount`**: Count of entries.
1961. **`winlog.event_data.ErrorMessage`**: Error message associated with the event.
1962. **`winlog.event_data.EventSourceId`**: ID of the event source.
1963. **`winlog.event_data.EventType`**: Type of the event.
1964. **`winlog.event_data.ExitReason`**: Reason for exiting.
1965. **`winlog.event_data.ExtraInfo`**: Additional information about the event.
1966. **`winlog.event_data.FailureName`**: Name of the failure.
1967. **`winlog.event_data.FailureNameLength`**: Length of the failure name.
1968. **`winlog.event_data.FailureReason`**: Reason for the failure.
1969. **`winlog.event_data.FileVersion`**: Version of the file involved.
1970. **`winlog.event_data.FilterOrigin`**: Origin of the filter.
1971. **`winlog.event_data.FilterRTID`**: RTID of the filter.
1972. **`winlog.event_data.FinalStatus`**: Final status of the event.
1973. **`winlog.event_data.FirstRefresh`**: Timestamp of the first refresh.
1974. **`winlog.event_data.Flags`**: Flags associated with the event.
1975. **`winlog.event_data.FlightSigning`**: Whether flight signing is enabled.
1976. **`winlog.event_data.ForceLogoff`**: Whether a forced logoff occurred.
1977. **`winlog.event_data.GrantedAccess`**: Access granted to the object.
1978. **`winlog.event_data.Group`**: Group involved in the event.
1979. **`winlog.event_data.GroupTypeChange`**: Change made to the group type.
1980. **`winlog.event_data.HandleId`**: ID of the handle.
1981. **`winlog.event_data.Hashes`**: Hashes of files or data involved.
1982. **`winlog.event_data.HasRemoteDynamicKeywordAddress`**: Whether a remote dynamic keyword address is used.
1983. **`winlog.event_data.HiveName`**: Name of the registry hive.
1984. **`winlog.event_data.HiveNameLength`**: Length of the hive name.
1985. **`winlog.event_data.HomeDirectory`**: Home directory of the user.
1986. **`winlog.event_data.HomePath`**: Path to the home directory.
1987. **`winlog.event_data.HypervisorDebug`**: Whether hypervisor debugging is enabled.
1988. **`winlog.event_data.HypervisorLaunchType`**: Type of hypervisor launch.
1989. **`winlog.event_data.HypervisorLoadOptions`**: Options for loading the hypervisor.
1990. **`winlog.event_data.Identity`**: Identity involved in the event.
1991. **`winlog.event_data.IdleImplementation`**: Implementation of idle detection.
1992. **`winlog.event_data.IdleStateCount`**: Count of idle states.
1993. **`winlog.event_data.Image`**: Image involved in the event.
1994. **`winlog.event_data.ImageLoaded`**: Whether an image was loaded.
1995. **`winlog.event_data.ImagePath`**: Path to the image.
1996. **`winlog.event_data.ImpersonationLevel`**: Level of impersonation.
1997. **`winlog.event_data.Initiated`**: Whether the event was initiated.
1998. **`winlog.event_data.IntegrityLevel`**: Integrity level of the process.
1999. **`winlog.event_data.InterfaceIndex`**: Index of the network interface.
2000. **`winlog.event_data.IpAddress`**: IP address involved.
2001. **`winlog.event_data.IpPort`**: Port number associated with the IP address.
2002. **`winlog.event_data.IsExecutable`**: Whether the file is executable.
2003. **`winlog.event_data.IsLoopback`**: Whether the connection is a loopback.
2004. **`winlog.event_data.IsTestConfig`**: Whether this is a test configuration.
2005. **`winlog.event_data.KerberosPolicyChange`**: Change made to Kerberos policy.
2006. **`winlog.event_data.KernelDebug`**: Whether kernel debugging is enabled.
2007. **`winlog.event_data.KeyFilePath`**: Path to the key file.
2008. **`winlog.event_data.KeyLength`**: Length of the key.
2009. **`winlog.event_data.KeyName`**: Name of the key.
2010. **`winlog.event_data.KeysUpdated`**: Whether keys were updated.
2011. **`winlog.event_data.KeyType`**: Type of the key.
2012. **`winlog.event_data.LastBootGood`**: Whether the last boot was successful.
2013. **`winlog.event_data.LastBootId`**: ID of the last boot.
2014. **`winlog.event_data.LastShutdownGood`**: Whether the last shutdown was successful.
2015. **`winlog.event_data.LayerName`**: Name of the layer.
2016. **`winlog.event_data.LayerNameDescription`**: Description of the layer name.
2017. **`winlog.event_data.LayerRTID`**: RTID of the layer.
2018. **`winlog.event_data.LmPackageName`**: Name of the Lm package.
2019. **`winlog.event_data.LoadOptions`**: Options used during loading.
2020. **`winlog.event_data.LockoutDuration`**: Duration of the lockout.
2021. **`winlog.event_data.LockoutObservationWindow`**: Window for observing lockouts.
2022. **`winlog.event_data.LockoutThreshold`**: Threshold for lockouts.
2023. **`winlog.event_data.LogonGuid`**: GUID of the logon session.
2024. **`winlog.event_data.LogonHours`**: Hours during which logon is allowed.
2025. **`winlog.event_data.LogonId`**: ID of the logon session.
2026. **`winlog.event_data.LogonProcessName`**: Name of the logon process.
2027. **`winlog.event_data.LogonType`**: Type of logon (e.g., interactive, network).
2028. **`winlog.event_data.MachineAccountQuota`**: Quota for machine accounts.
2029. **`winlog.event_data.MajorVersion`**: Major version number.
2030. **`winlog.event_data.MandatoryLabel`**: Mandatory label applied.
2031. **`winlog.event_data.MaximumPerformancePercent`**: Maximum performance percentage.
2032. **`winlog.event_data.MaxPasswordAge`**: Maximum age of a password.
2033. **`winlog.event_data.MemberName`**: Name of the member.
2034. **`winlog.event_data.MemberSid`**: SID of the member.
2035. **`winlog.event_data.MinimumPasswordLength`**: Minimum length of a password.
2036. **`winlog.event_data.MinimumPasswordLengthAudit`**: Whether auditing is enabled for minimum password length.
2037. **`winlog.event_data.MinimumPerformancePercent`**: Minimum performance percentage.
2038. **`winlog.event_data.MinimumThrottlePercent`**: Minimum throttle percentage.
2039. **`winlog.event_data.MinorVersion`**: Minor version number.
2040. **`winlog.event_data.MinPasswordAge`**: Minimum age of a password.
2041. **`winlog.event_data.MinPasswordLength`**: Minimum length of a password.
2042. **`winlog.event_data.MixedDomainMode`**: Whether mixed domain mode is enabled.
2043. **`winlog.event_data.MonitorReason`**: Reason for monitoring.
2044. **`winlog.event_data.NewProcessId`**: ID of the new process.
2045. **`winlog.event_data.NewProcessName`**: Name of the new process.
2046. **`winlog.event_data.NewSchemeGuid`**: GUID of the new scheme.
2047. **`winlog.event_data.NewSd`**: New security descriptor.
2048. **`winlog.event_data.NewSdDacl0`**: New DACL (Discretionary Access Control List) for the security descriptor.
2049. **`winlog.event_data.NewSdDacl1`**: Additional DACL for the security descriptor.
2050. **`winlog.event_data.NewSdDacl2`**: Further DACL for the security descriptor.
2051. **`winlog.event_data.NewSdSacl0`**: New SACL (System Access Control List) for the security descriptor.
2052. **`winlog.event_data.NewSdSacl1`**: Additional SACL for the security descriptor.
2053. **`winlog.event_data.NewSdSacl2`**: Further SACL for the security descriptor.
2054. **`winlog.event_data.NewSize`**: New size of a file or object.
2055. **`winlog.event_data.NewTargetUserName`**: New target username.
2056. **`winlog.event_data.NewThreadId`**: ID of the new thread.
2057. **`winlog.event_data.NewTime`**: New timestamp.
2058. **`winlog.event_data.NewUACList`**: New UAC (User Account Control) list.
2059. **`winlog.event_data.NewUacValue`**: New UAC value.
2060. **`winlog.event_data.NextSessionId`**: ID of the next session.
2061. **`winlog.event_data.NextSessionType`**: Type of the next session.
2062. **`winlog.event_data.NominalFrequency`**: Nominal frequency of an event.
2063. **`winlog.event_data.Number`**: Number associated with the event.
2064. **`winlog.event_data.ObjectName`**: Name of the object involved.
2065. **`winlog.event_data.ObjectServer`**: Server hosting the object.
2066. **`winlog.event_data.ObjectType`**: Type of the object.
2067. **`winlog.event_data.OemInformation`**: OEM information.
2068. **`winlog.event_data.OldSchemeGuid`**: Old scheme GUID.
2069. **`winlog.event_data.OldSd`**: Old security descriptor.
2070. **`winlog.event_data.OldSdDacl0`**: Old DACL for the security descriptor.
2071. **`winlog.event_data.OldSdDacl1`**: Additional old DACL for the security descriptor.
2072. **`winlog.event_data.OldSdDacl2`**: Further old DACL for the security descriptor.
2073. **`winlog.event_data.OldSdSacl0`**: Old S
2074. **`winlog.event_data.ParentProcessGuid`**: GUID of the parent process.
2075. **`winlog.event_data.ParentProcessId`**: ID of the parent process.
2076. **`winlog.event_data.ParentProcessName`**: Name of the parent process.
2077. **`winlog.event_data.ParentUser`**: User associated with the parent process.
2078. **`winlog.event_data.PasswordHistoryLength`**: Length of the password history.
2079. **`winlog.event_data.PasswordLastSet`**: Timestamp when the password was last set.
2080. **`winlog.event_data.PasswordProperties`**: Properties of the password.
2081. **`winlog.event_data.Path`**: Path associated with the event.
2082. **`winlog.event_data.PerformanceImplementation`**: Implementation details for performance-related events.
2083. **`winlog.event_data.PipeName`**: Name of the pipe used in the event.
2084. **`winlog.event_data.PowerStateAc`**: Power state of the system (AC).
2085. **`winlog.event_data.PreAuthType`**: Type of pre-authentication used.
2086. **`winlog.event_data.PreviousCreationUtcTime`**: Timestamp of the previous creation in UTC.
2087. **`winlog.event_data.PreviousEnergyCapacityAtEnd`**: Previous energy capacity at the end of an event.
2088. **`winlog.event_data.PreviousEnergyCapacityAtStart`**: Previous energy capacity at the start of an event.
2089. **`winlog.event_data.PreviousFullEnergyCapacityAtEnd`**: Previous full energy capacity at the end of an event.
2090. **`winlog.event_data.PreviousFullEnergyCapacityAtStart`**: Previous full energy capacity at the start of an event.
2091. **`winlog.event_data.PreviousSessionDurationInUs`**: Duration of the previous session in microseconds.
2092. **`winlog.event_data.PreviousSessionId`**: ID of the previous session.
2093. **`winlog.event_data.PreviousSessionType`**: Type of the previous session.
2094. **`winlog.event_data.PreviousTime`**: Timestamp of the previous event.
2095. **`winlog.event_data.PrimaryGroupId`**: ID of the primary group.
2096. **`winlog.event_data.PrivilegeList`**: List of privileges involved.
2097. **`winlog.event_data.ProcessCreationTime`**: Timestamp when the process was created.
2098. **`winlog.event_data.ProcessGuid`**: GUID of the process.
2099. **`winlog.event_data.ProcessId`**: ID of the process.
2100. **`winlog.event_data.ProcessID`**: Another representation of the process ID.
2101. **`winlog.event_data.ProcessingMode`**: Mode used for processing the event.
2102. **`winlog.event_data.ProcessingTimeInMilliseconds`**: Time taken to process the event in milliseconds.
2103. **`winlog.event_data.ProcessName`**: Name of the process.
2104. **`winlog.event_data.ProcessPath`**: Path to the process executable.
2105. **`winlog.event_data.ProcessPid`**: Another representation of the process PID.
2106. **`winlog.event_data.Product`**: Product name associated with the event.
2107. **`winlog.event_data.ProfilePath`**: Path to the profile.
2108. **`winlog.event_data.Protocol`**: Protocol used in the event.
2109. **`winlog.event_data.ProviderName`**: Name of the provider that logged the event.
2110. **`winlog.event_data.PuaCount`**: Count of potentially unwanted applications (PUA).
2111. **`winlog.event_data.PuaPolicyId`**: ID of the PUA policy.
2112. **`winlog.event_data.QfeVersion`**: Version of the Quick Fix Engineering (QFE) update.
2113. **`winlog.event_data.QueryName`**: Name of the query.
2114. **`winlog.event_data.QueryResults`**: Results of the query.
2115. **`winlog.event_data.QueryStatus`**: Status of the query.
2116. **`winlog.event_data.ReadOperation`**: Type of read operation performed.
2117. **`winlog.event_data.Reason`**: Reason for the event.
2118. **`winlog.event_data.RelativeTargetName`**: Relative name of the target.
2119. **`winlog.event_data.RelaxMinimumPasswordLengthLimits`**: Whether minimum password length limits are relaxed.
2120. **`winlog.event_data.RemoteEventLogging`**: Whether remote event logging is enabled.
2121. **`winlog.event_data.RemoteMachineDescription`**: Description of the remote machine.
2122. **`winlog.event_data.RemoteMachineID`**: ID of the remote machine.
2123. **`winlog.event_data.RemoteUserDescription`**: Description of the remote user.
2124. **`winlog.event_data.RemoteUserID`**: ID of the remote user.
2125. **`winlog.event_data.Resource`**: Resource involved in the event.
2126. **`winlog.event_data.ResourceAttributes`**: Attributes of the resource.
2127. **`winlog.event_data.RestrictedAdminMode`**: Whether restricted admin mode is enabled.
2128. **`winlog.event_data.RetryMinutes`**: Number of minutes to retry an operation.
2129. **`winlog.event_data.ReturnCode`**: Return code from an operation.
2130. **`winlog.event_data.RuleName`**: Name of the rule involved.
2131. **`winlog.event_data.SamAccountName`**: SAM account name.
2132. **`winlog.event_data.Schema`**: Schema used in the event.
2133. **`winlog.event_data.SchemaFriendlyName`**: Friendly name of the schema.
2134. **`winlog.event_data.SchemaVersion`**: Version of the schema.
2135. **`winlog.event_data.ScriptBlockText`**: Text of the script block.
2136. **`winlog.event_data.ScriptPath`**: Path to the script.
2137. **`winlog.event_data.SearchString`**: String used for searching.
2138. **`winlog.event_data.Service`**: Service involved in the event.
2139. **`winlog.event_data.ServiceAccount`**: Account used by the service.
2140. **`winlog.event_data.ServiceFileName`**: Name of the service file.
2141. **`winlog.event_data.serviceGuid`**: GUID of the service.
2142. **`winlog.event_data.ServiceName`**: Name of the service.
2143. **`winlog.event_data.ServicePrincipalNames`**: Service principal names.
2144. **`winlog.event_data.ServiceSid`**: SID of the service.
2145. **`winlog.event_data.ServiceStartType`**: Type of service start (e.g., automatic, manual).
2146. **`winlog.event_data.ServiceType`**: Type of the service.
2147. **`winlog.event_data.ServiceVersion`**: Version of the service.
2148. **`winlog.event_data.SessionName`**: Name of the session.
2149. **`winlog.event_data.ShareLocalPath`**: Local path of the shared resource.
2150. **`winlog.event_data.ShareName`**: Name of the shared resource.
2151. **`winlog.event_data.ShutdownActionType`**: Type of shutdown action.
2152. **`winlog.event_data.ShutdownEventCode`**: Event code for shutdown.
2153. **`winlog.event_data.ShutdownReason`**: Reason for shutdown.
2154. **`winlog.event_data.SidFilteringEnabled`**: Whether SID filtering is enabled.
2155. **`winlog.event_data.SidHistory`**: SID history.
2156. **`winlog.event_data.Signature`**: Signature associated with the event.
2157. **`winlog.event_data.SignatureStatus`**: Status of the signature.
2158. **`winlog.event_data.Signed`**: Whether the event is signed.
2159. **`winlog.event_data.SourceAddress`**: Address of the source.
2160. **`winlog.event_data.SourceHostname`**: Hostname of the source.
2161. **`winlog.event_data.SourceImage`**: Image associated with the source.
2162. **`winlog.event_data.SourceIp`**: IP address of the source.
2163. **`winlog.event_data.SourceIsIpv6`**: Whether the source IP is IPv6.
2164. **`winlog.event_data.SourcePort`**: Port number of the source.
2165. **`winlog.event_data.SourcePortName`**: Name of the source port.
2166. **`winlog.event_data.SourceProcessGuid`**: GUID of the source process.
2167. **`winlog.event_data.SourceProcessId`**: ID of the source process.
2168. **`winlog.event_data.SourceThreadId`**: ID of the source thread.
2169. **`winlog.event_data.SourceUser`**: User associated with the source.
2170. **`winlog.event_data.StartAddress`**: Starting address of the event.
2171. **`winlog.event_data.StartFunction`**: Starting function of the event.
2172. **`winlog.event_data.StartModule`**: Starting module of the event.
2173. **`winlog.event_data.StartTime`**: Timestamp when the event started.
2174. **`winlog.event_data.StartType`**: Type of start (e.g., automatic, manual).
2175. **`winlog.event_data.State`**: State of the event.
2176. **`winlog.event_data.Status`**: Status of the event.
2177. **`winlog.event_data.StatusDescription`**: Description of the status.
2178. **`winlog.event_data.StopTime`**: Timestamp when the event stopped.
2179. **`winlog.event_data.SubCategory`**: Subcategory of the event.
2180. **`winlog.event_data.SubcategoryGuid`**: GUID of the subcategory.
2181. **`winlog.event_data.SubCategoryId`**: ID of the subcategory.
2182. **`winlog.event_data.SubjectDomainName`**: Domain name of the subject.
2183. **`winlog.event_data.SubjectLogonId`**: Logon ID of the subject.
2184. **`winlog.event_data.SubjectUserName`**: Username of the subject.
2185. **`winlog.event_data.SubjectUserSid`**: SID of the subject user.
2186. **`winlog.event_data.SubStatus`**: Substatus of the event.
2187. **`winlog.event_data.SupportInfo1`**: First support information.
2188. **`winlog.event_data.SupportInfo2`**: Second support information.
2189. **`winlog.event_data.TargetDomainName`**: Domain name of the target.
2190. **`winlog.event_data.TargetFilename`**: Filename of the target.
2191. **`winlog.event_data.TargetImage`**: Image associated with the target.
2192. **`winlog.event_data.TargetInfo`**: Information about the target.
2193. **`winlog.event_data.TargetLinkedLogonId`**: Linked logon ID of the target.
2194. **`winlog.event_data.TargetLogonGuid`**: GUID of the target logon.
2195. **`winlog.event_data.TargetLogonId`**: Logon ID of the target.
2196. **`winlog.event_data.TargetName`**: Name of the target.
2197. **`winlog.event_data.TargetObject`**: Object associated with the target.
2198. **`winlog.event_data.TargetOutboundDomainName`**: Outbound domain name of the target.
2199. **`winlog.event_data.TargetOutboundUserName`**: Outbound username of the target.
2200. **`winlog.event_data.TargetProcessGuid`**: GUID of the target process.
2201. **`winlog.event_data.TargetProcessId`**: ID of the target process.
2202. **`winlog.event_data.TargetProcessName`**: Name of the target process.
2203. **`winlog.event_data.TargetServerName`**: Name of the target server.
2204. **`winlog.event_data.TargetSid`**: SID of the target.
2205. **`winlog.event_data.TargetUser`**: User associated with the target.
2206. **`winlog.event_data.TargetUserName`**: Username of the target.
2207. **`winlog.event_data.TargetUserSid`**: SID of the target user.
2208. **`winlog.event_data.TdoAttributes`**: Attributes of the TDO (Trusted Domain Object).
2209. **`winlog.event_data.TdoDirection`**: Direction of the TDO.
2210. **`winlog.event_data.TdoType`**: Type of the TDO.
2211. **`winlog.event_data.TerminalSessionId`**: ID of the terminal session.
2212. **`winlog.event_data.TestSigning`**: Whether test signing is enabled.
2213. **`winlog.event_data.TicketEncryptionType`**: Type of ticket encryption.
2214. **`winlog.event_data.TicketEncryptionTypeDescription`**: Description of the ticket encryption type.
2215. **`winlog.event_data.TicketOptions`**: Options for ticket encryption.
2216. **`winlog.event_data.TicketOptionsDescription`**: Description of the ticket options.
2217. **`winlog.event_data.TimeSource`**: Source of the time.
2218. **`winlog.event_data.TimeSourceRefId`**: Reference ID of the time source.
2219. **`winlog.event_data.TimeZoneInfoCacheUpdated`**: Whether the time zone info cache was updated.
2220. **`winlog.event_data.TokenElevationType`**: Type of token elevation.
2221. **`winlog.event_data.TransmittedServices`**: Services transmitted.
2222. **`winlog.event_data.TSId`**: ID of the terminal server.
2223. **`winlog.event_data.Type`**: Type of the event.
2224. **`winlog.event_data.updateGuid`**: GUID of the update.
2225. **`winlog.event_data.UpdateReason`**: Reason for the update.
2226. **`winlog.event_data.updateRevisionNumber`**: Revision number of the update.
2227. **`winlog.event_data.updateTitle`**: Title of the update.
2228. **`winlog.event_data.User`**: User involved in the event.
2229. **`winlog.event_data.UserAccountControl`**: User account control flags.
2230. **`winlog.event_data.UserParameters`**: Parameters for the user.
2231. **`winlog.event_data.UserPrincipalName`**: User principal name.
2232. **`winlog.event_data.UserSid`**: SID of the user.
2233. **`winlog.event_data.UserWorkstations`**: Workstations allowed for the user.
2234. **`winlog.event_data.UtcTime`**: Timestamp in UTC.
2235. **`winlog.event_data.Version`**: Version of the event.
2236. **`winlog.event_data.VirtualAccount`**: Whether a virtual account is used.
2237. **`winlog.event_data.VsmLaunchType`**: Type of VSM (Virtual Secure Mode) launch.
2238. **`winlog.event_data.VsmPolicy`**: Policy for VSM.
2239. **`winlog.event_data.Workstation`**: Workstation involved.
2240. **`winlog.event_data.WorkstationName`**: Name of the workstation.
2241. **`winlog.event_id`**: ID of the event.
2242. **`winlog.keywords`**: Keywords associated with the event.
2243. **`winlog.level`**: Severity level of the event.
2244. **`winlog.logon.failure.reason`**: Reason for logon failure.
2245. **`winlog.logon.failure.status`**: Status of logon failure.
2246. **`winlog.logon.failure.sub_status`**: Substatus of logon failure.
2247. **`winlog.logon.id`**: ID of the logon event.
2248. **`winlog.logon.type`**: Type of logon.
2249. **`winlog.opcode`**: Opcode of the event.
2250. **`winlog.outcome`**: Outcome of the event.
2251. **`winlog.process.pid`**: PID of the process involved in the event.
2252. **`winlog.process.thread.id`**: ID of the thread within a process.
2253. **`winlog.provider_guid`**: GUID of the provider that logged the event.
2254. **`winlog.provider_name`**: Name of the provider that logged the event.
2255. **`winlog.record_id`**: Record ID of the event log entry.
2256. **`winlog.related_activity_id`**: ID of related activities.
2257. **`winlog.task`**: Task associated with the event.
2258. **`winlog.time_created`**: Timestamp when the event was created.
2259. **`winlog.trustAttribute`**: Attribute related to trust settings.
2260. **`winlog.trustDirection`**: Direction of trust (e.g., inbound, outbound).
2261. **`winlog.trustType`**: Type of trust (e.g., forest, domain).
2262. **`winlog.user_data.ActiveOperation`**: Active operation associated with the user data.
2263. **`winlog.user_data.BackupPath`**: Path used for backup operations.
2264. **`winlog.user_data.binaryData`**: Binary data associated with the event.
2265. **`winlog.user_data.binaryDataSize`**: Size of the binary data.
2266. **`winlog.user_data.Channel`**: Channel associated with the user data.
2267. **`winlog.user_data.DetectedBy`**: Entity that detected the event.
2268. **`winlog.user_data.ExitCode`**: Exit code of a process or operation.
2269. **`winlog.user_data.FriendlyName`**: Friendly name of an object or process.
2270. **`winlog.user_data.InstanceId`**: ID of an instance.
2271. **`winlog.user_data.LifetimeId`**: Lifetime ID of an object or process.
2272. **`winlog.user_data.Location`**: Location associated with the event.
2273. **`winlog.user_data.Message`**: Message associated with the event.
2274. **`winlog.user_data.param1`**: First parameter of the event.
2275. **`winlog.user_data.param2`**: Second parameter of the event.
2276. **`winlog.user_data.Problem`**: Problem description associated with the event.
2277. **`winlog.user_data.RestartCount`**: Number of restarts.
2278. **`winlog.user_data.RmSessionId`**: Session ID for remote management.
2279. **`winlog.user_data.Status`**: Status of the event or operation.
2280. **`winlog.user_data.SubjectDomainName`**: Domain name of the subject.
2281. **`winlog.user_data.SubjectLogonId`**: Logon ID of the subject.
2282. **`winlog.user_data.SubjectUserName`**: Username of the subject.
2283. **`winlog.user_data.SubjectUserSid`**: SID of the subject user.
2284. **`winlog.user_data.UTCStartTime`**: Start time in UTC.
2285. **`winlog.user_data.xml_name`**: XML name associated with the event.
2286. **`winlog.user.domain`**: Domain of the user.
2287. **`winlog.user.identifier`**: Identifier of the user.
2288. **`winlog.user.name`**: Name of the user.
2289. **`winlog.user.type`**: Type of the user.
2290. **`winlog.version`**: Version of the event log format.
