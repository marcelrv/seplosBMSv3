# SPA & PCT Table

## SPA Table
Settings


| **"ID"** | **rtuAddress** | **description zh-CN** | **description en-US**                       | **byte** | **value** | **Index** | **unit** | **scale** | **hasSign** | **isDisplay** | **datatype**     | **attribute** |
|----------|----------------|-----------------------|---------------------------------------------|----------|-----------|-----------|----------|-----------|-------------|---------------|------------------|---------------|
| 1        | 1300           | 电芯温度数目                | Ntc number                                  | 2        | 0         | 0         | num      | 1         | 0           | 1             | IntParameterInfo | Normal        |
| 2        | 1301           | 串联电池节数                | Serial battery number                       | 2        | 0         | 2         | num      | 1         | 0           | 1             | IntParameterInfo | Normal        |
| 3        | 1302           | 总压高压恢复                | Battery high voltage recovery               | 2        | 0         | 4         | V        | 0.01      | 0           | 1             | IntParameterInfo | Normal        |
| 4        | 1303           | 总压高压告警                | Battery high voltage alarm                  | 2        | 0         | 6         | V        | 0.01      | 0           | 1             | IntParameterInfo | Normal        |
| 5        | 1304           | 总压过压恢复                | Battery over voltage recovery               | 2        | 0         | 8         | V        | 0.01      | 0           | 1             | IntParameterInfo | Normal        |
| 6        | 1305           | 总压过压保护                | Battery over voltage protection             | 2        | 0         | 10        | V        | 0.01      | 0           | 1             | IntParameterInfo | Normal        |
| 7        | 1306           | 总压低压恢复                | Battery low voltage recovery                | 2        | 0         | 12        | V        | 0.01      | 0           | 1             | IntParameterInfo | Normal        |
| 8        | 1307           | 总压低压告警                | Battery low voltage alarm                   | 2        | 0         | 14        | V        | 0.01      | 0           | 1             | IntParameterInfo | Normal        |
| 9        | 1308           | 总压欠压恢复                | Battery under voltage recovery              | 2        | 0         | 16        | V        | 0.01      | 0           | 1             | IntParameterInfo | Normal        |
| 10       | 1309           | 总压欠压保护                | Battery under voltage protection            | 2        | 0         | 18        | V        | 0.01      | 0           | 1             | IntParameterInfo | Normal        |
| 11       | 130A           | 单体高压恢复                | Cell high voltage recovery                  | 2        | 0         | 20        | V        | 0.001     | 0           | 1             | IntParameterInfo | Normal        |
| 12       | 130B           | 单体高压告警                | Cell high voltage alarm                     | 2        | 0         | 22        | V        | 0.001     | 0           | 1             | IntParameterInfo | Normal        |
| 13       | 130C           | 单体过压恢复                | Cell over voltage recovery                  | 2        | 0         | 24        | V        | 0.001     | 0           | 1             | IntParameterInfo | Normal        |
| 14       | 130D           | 单体过压保护                | Cell over voltage protection                | 2        | 0         | 26        | V        | 0.001     | 0           | 1             | IntParameterInfo | Normal        |
| 15       | 130E           | 单体低压恢复                | Cell low voltage recovery                   | 2        | 0         | 28        | V        | 0.001     | 0           | 1             | IntParameterInfo | Normal        |
| 16       | 130F           | 单体低压告警                | Cell low voltage alarm                      | 2        | 0         | 30        | V        | 0.001     | 0           | 1             | IntParameterInfo | Normal        |
| 17       | 1310           | 单体欠压恢复                | Cell under voltage recovery                 | 2        | 0         | 32        | V        | 0.001     | 0           | 1             | IntParameterInfo | Normal        |
| 18       | 1311           | 单体欠压保护                | Cell under voltage protection               | 2        | 0         | 34        | V        | 0.001     | 0           | 1             | IntParameterInfo | Normal        |
| 19       | 1312           | 电芯欠压失效                | Cell under voltage failure                  | 2        | 0         | 36        | V        | 0.001     | 0           | 1             | IntParameterInfo | Normal        |
| 20       | 1313           | 单体压差保护                | Cell diff pressure protection               | 2        | 0         | 38        | V        | 0.001     | 0           | 1             | IntParameterInfo | Normal        |
| 21       | 1314           | 压差保护恢复                | Diff pressure protection recovery           | 2        | 0         | 40        | V        | 0.001     | 0           | 1             | IntParameterInfo | Normal        |
| 22       | 1315           | 充电过流恢复                | Charge over current recovery                | 2        | 0         | 42        | A        | 1         | 1           | 1             | IntParameterInfo | Normal        |
| 23       | 1316           | 充电过流告警                | Charge over current alarm                   | 2        | 0         | 44        | A        | 1         | 1           | 1             | IntParameterInfo | Normal        |
| 24       | 1317           | 充电过流保护                | Charge over current protection              | 2        | 0         | 46        | A        | 1         | 1           | 1             | IntParameterInfo | Normal        |
| 25       | 1318           | 充电过流延时                | Charge over current delay                   | 2        | 0         | 48        | s        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 26       | 1319           | 充电二级过流保护              | Secondary charge over current protection    | 2        | 0         | 50        | A        | 1         | 1           | 1             | IntParameterInfo | Normal        |
| 27       | 131A           | 充电二级过流延时              | Secondary charge over current delay         | 2        | 0         | 52        | ms       | 1         | 0           | 1             | IntParameterInfo | Normal        |
| 28       | 131B           | 放电过流恢复                | Discharge over current recovery             | 2        | 0         | 54        | A        | 1         | 1           | 1             | IntParameterInfo | Normal        |
| 29       | 131C           | 放电过流告警                | Discharge over current alarm                | 2        | 0         | 56        | A        | 1         | 1           | 1             | IntParameterInfo | Normal        |
| 30       | 131D           | 放电过流保护                | Discharge over current protection           | 2        | 0         | 58        | A        | 1         | 1           | 1             | IntParameterInfo | Normal        |
| 31       | 131E           | 放电过流延时                | Discharge over current delay                | 2        | 0         | 60        | s        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 32       | 131F           | 放电二级过流保护              | Secondary discharge over current protection | 2        | 0         | 62        | A        | 1         | 1           | 1             | IntParameterInfo | Normal        |
| 33       | 1320           | 放电二级过流延时              | Secondary discharge over current  delay     | 2        | 0         | 64        | ms       | 1         | 0           | 1             | IntParameterInfo | Normal        |
| 34       | 1321           | 输出短路保护                | Output short-circuit protection             | 2        | 0         | 66        | A        | 1         | 1           | 0             | IntParameterInfo | Normal        |
| 35       | 1322           | 输出短路延时                | Output short-circuit  delay                 | 2        | 0         | 68        | us       | 1         | 0           | 0             | IntParameterInfo | Normal        |
| 36       | 1323           | 过流恢复延时                | Over current recovery delay                 | 2        | 0         | 70        | s        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 37       | 1324           | 过流锁定次数                | Number of over current lock times           | 2        | 0         | 72        | times    | 1         | 0           | 1             | IntParameterInfo | Normal        |
| 38       | 1325           | 充电限流持续时间              | Charge current Limit duration               | 2        | 0         | 74        | s        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 39       | 1326           | 脉冲限流电流                | Pluse current limiting current              | 2        | 0         | 76        | A        | 1         | 0           | 1             | IntParameterInfo | Normal        |
| 40       | 1327           | 脉冲限流时间                | Pluse current limiting time                 | 2        | 0         | 78        | s        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 41       | 1328           | 浮充锁定电压                | Float charge locking voltage                | 2        | 0         | 80        | V        | 0.001     | 0           | 0             | IntParameterInfo | Normal        |
| 42       | 1329           | 浮充解除电压                | Float charge release voltage                | 2        | 0         | 82        | V        | 0.001     | 0           | 0             | IntParameterInfo | Normal        |
| 43       | 132A           | 浮充锁定电流                | Float charge locking current                | 2        | 0         | 84        | mA       | 1         | 0           | 0             | IntParameterInfo | Normal        |
| 44       | 132B           | 短路预充完成率               | Short-circuit precharge completion rate     | 2        | 0         | 86        | %        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 45       | 132C           | 正常预充完成率               | Normal precharge completion rate            | 2        | 0         | 88        | %        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 46       | 132D           | 异常预充完成率               | Abnormal precharge completion rate          | 2        | 0         | 90        | %        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 47       | 132E           | 预充超时时间                | Precharge over time                         | 2        | 0         | 92        | s        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 48       | 132F           | 充电高温恢复                | Charge high temperature recovery            | 2        | 0         | 94        | ℃        | 0.1       | 1           | 1             | IntParameterInfo | Normal        |
| 49       | 1330           | 充电高温告警                | Charge high temperature alarm               | 2        | 0         | 96        | ℃        | 0.1       | 1           | 1             | IntParameterInfo | Normal        |
| 50       | 1331           | 充电过温恢复                | Charge over temperature recovery            | 2        | 0         | 98        | ℃        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 51       | 1332           | 充电过温保护                | Charge over temperature protection          | 2        | 0         | 100       | ℃        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 52       | 1333           | 充电低温恢复                | Charge low temperature recovery             | 2        | 0         | 102       | ℃        | 0.1       | 1           | 1             | IntParameterInfo | Normal        |
| 53       | 1334           | 充电低温告警                | Charge low temperature alarm                | 2        | 0         | 104       | ℃        | 0.1       | 1           | 1             | IntParameterInfo | Normal        |
| 54       | 1335           | 充电欠温恢复                | Charge under temperature recovery           | 2        | 0         | 106       | ℃        | 0.1       | 1           | 1             | IntParameterInfo | Normal        |
| 55       | 1336           | 充电欠温保护                | Charge under temperature protection         | 2        | 0         | 108       | ℃        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 56       | 1337           | 放电高温恢复                | Discharge high temperature recovery         | 2        | 0         | 110       | ℃        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 57       | 1338           | 放电高温告警                | Discharge high temperature alarm            | 2        | 0         | 112       | ℃        | 0.1       | 1           | 1             | IntParameterInfo | Normal        |
| 58       | 1339           | 放电过温恢复                | Discharge over temperature recovery         | 2        | 0         | 114       | ℃        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 59       | 133A           | 放电过温保护                | Discharge over temperature protection       | 2        | 0         | 116       | ℃        | 0.1       | 1           | 1             | IntParameterInfo | Normal        |
| 60       | 133B           | 放电低温恢复                | Discharge low temperature recovery          | 2        | 0         | 118       | ℃        | 0.1       | 1           | 1             | IntParameterInfo | Normal        |
| 61       | 133C           | 放电低温告警                | Discharge low temperature alarm             | 2        | 0         | 120       | ℃        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 62       | 133D           | 放电欠温恢复                | Discharge under temperature recovery        | 2        | 0         | 122       | ℃        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 63       | 133E           | 放电欠温保护                | Discharge under temperature protection      | 2        | 0         | 124       | ℃        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 64       | 133F           | 环境高温恢复                | High ambient temperature recovery           | 2        | 0         | 126       | ℃        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 65       | 1340           | 环境高温告警                | High ambient temperature alarm              | 2        | 0         | 128       | ℃        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 66       | 1341           | 环境过温恢复                | Over ambient temperature recovery           | 2        | 0         | 130       | ℃        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 67       | 1342           | 环境过温保护                | Over ambient temperature protection         | 2        | 0         | 132       | ℃        | 0.1       | 1           | 1             | IntParameterInfo | Normal        |
| 68       | 1343           | 环境低温恢复                | Low ambient temperature recovery            | 2        | 0         | 134       | ℃        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 69       | 1344           | 环境低温告警                | Low ambient temperature alarm               | 2        | 0         | 136       | ℃        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 70       | 1345           | 环境欠温恢复                | Under ambient temperature recovery          | 2        | 0         | 138       | ℃        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 71       | 1346           | 环境欠温保护                | Under ambient temperature protection        | 2        | 0         | 140       | ℃        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 72       | 1347           | 功率高温恢复                | Power high temperature recovery             | 2        | 0         | 142       | ℃        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 73       | 1348           | 功率高温告警                | power high temperature alarm                | 2        | 0         | 144       | ℃        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 74       | 1349           | 功率过温恢复                | Power over temperature recovery             | 2        | 0         | 146       | ℃        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 75       | 134A           | 功率过温保护                | Power over temperature protection           | 2        | 0         | 148       | ℃        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 76       | 134B           | 温度调节关闭                | Temperature regulate stop                   | 2        | 0         | 150       | ℃        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 77       | 134C           | 温度调节开启                | Temperature regulate open                   | 2        | 0         | 152       | ℃        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 78       | 134D           | 均衡高温禁止                | Equalization high temperature prohibition   | 2        | 0         | 154       | ℃        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 79       | 134E           | 均衡低温禁止                | Equalization low temperature prohibition    | 2        | 0         | 156       | ℃        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 80       | 134F           | 静态均衡定时                | Static equalization timing                  | 2        | 0         | 158       | H        | 1         | 0           | 1             | IntParameterInfo | Normal        |
| 81       | 1350           | 均衡开启电压                | Equalization open voltage                   | 2        | 0         | 160       | V        | 0.001     | 0           | 1             | IntParameterInfo | Normal        |
| 82       | 1351           | 均衡开启压差                | Equalization open difference pressure       | 2        | 0         | 162       | V        | 0.001     | 0           | 1             | IntParameterInfo | Normal        |
| 83       | 1352           | 均衡结束压差                | Equalization stop difference pressure       | 2        | 0         | 164       | V        | 0.001     | 0           | 1             | IntParameterInfo | Normal        |
| 84       | 1353           | 补电 SOC                | Power supply SOC                            | 2        | 0         | 166       | %        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 85       | 1354           | SOC低恢复                | SOC low recovery                            | 2        | 0         | 168       | %        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 86       | 1355           | SOC低告警                | SOC low alarm                               | 2        | 0         | 170       | %        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 87       | 1356           | SOC保护恢复               | SOC protection recovery                     | 2        | 0         | 172       | %        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 88       | 1357           | SOC低保护                | SOC low protection                          | 2        | 0         | 174       | %        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 89       | 1358           | 电池额定容量                | Rated battery  capacity                     | 2        | 0         | 176       | Ah       | 0.01      | 0           | 1             | IntParameterInfo | Normal        |
| 90       | 1359           | 电池总容量                 | Total battery capacity                      | 2        | 0         | 178       | Ah       | 0.01      | 0           | 1             | IntParameterInfo | Normal        |
| 91       | 135A           | 电池剩余容量                | Battery remaining capacity                  | 2        | 0         | 180       | Ah       | 0.01      | 0           | 1             | IntParameterInfo | Normal        |
| 92       | 135B           | 待机休眠定时                | Stand-by time                               | 2        | 0         | 182       | H        | 1         | 0           | 1             | IntParameterInfo | Normal        |
| 93       | 135C           | 强制输出延迟                | Forced output delay                         | 2        | 0         | 184       | s        | 0.1       | 0           | 1             | IntParameterInfo | Normal        |
| 94       | 135D           | 强制输出间隔                | Forced output splite                        | 2        | 0         | 186       | Min      | 1         | 0           | 1             | IntParameterInfo | Normal        |
| 95       | 135E           | 强制输出次数                | Number of forced output                     | 2        | 0         | 188       | times    | 1         | 0           | 1             | IntParameterInfo | Normal        |
| 96       | 135F           | 补偿位点1                 | Compensation site 1                         | 2        | 0         | 190       | Cell     | 1         | 0           | 1             | IntParameterInfo | Normal        |
| 97       | 1360           | 补偿位点1电阻               | Compensation site 1 resistance              | 2        | 0         | 192       | mΩ       | 1         | 0           | 1             | IntParameterInfo | Normal        |
| 98       | 1361           | 补偿位点2                 | Compensating site 2                         | 2        | 0         | 194       | Cell     | 1         | 0           | 1             | IntParameterInfo | Normal        |
| 99       | 1362           | 补偿位点2电阻               | Compensation site 2 resistance              | 2        | 0         | 196       | mΩ       | 1         | 0           | 1             | IntParameterInfo | Normal        |
| 100      | 1363           | 单体压差告警                | Cell diff pressure alarm                    | 2        | 0         | 198       | mV       | 1         | 0           | 1             | IntParameterInfo | Normal        |
| 101      | 1364           | 压差告警恢复                | Diff pressure alarm recovery                | 2        | 0         | 200       | mV       | 1         | 0           | 1             | IntParameterInfo | Normal        |
| 102      | 1365           | 充电请求电压                | Charging request voltage                    | 2        | 0         | 202       | V        | 0.01      | 0           | 1             | IntParameterInfo | Normal        |
| 103      | 1366           | 充电请求电流                | Charging request current                    | 2        | 0         | 204       | A        | 1         | 0           | 1             | IntParameterInfo | Normal        |
| 104      | 1367           | 放电请求电流                | Discharge request current                   | 2        | 0         | 206       | A        | 1         | 0           | 1             | IntParameterInfo | Normal        |
| 105      | 1368           | PCS协议                 | Pcs protocol                                | 2        | 0         | 208       | PPT      | 1         | 0           | 0             | IntParameterInfo | Normal        |
| 106      | 1369           | 检流器校正因子               | Current detector correction factor          | 2        | 0         | 210       | 0.1      | 1         | 0           | 0             | IntParameterInfo | Normal        |

## PCT Table

Protocol selection options related to register 0x1368 pcs protocol

| **"ID"** | **protocolName** | **字段1**  |
|----------|------------------|----------|
| 0        | Pylon_CAN        | 派能       |
| 1        | Growatt_CAN      | 古瑞瓦特     |
| 2        | Goodwe_CAN       | 固德威      |
| 3        | Sofar_CAN        | 首航       |
| 4        | SMA_CAN          | SMA      |
| 5        | Victron_CAN      | Victron  |
| 6        | Studer_CAN       | Studer   |
| 7        | Ginlong_CAN      | 锦浪       |
| 8        | Voltronic_485    | 日月元      |
| 9        | Srne_485         | 硕日       |
| 10       | Growatt_485      | 古瑞瓦特     |
| 11       | Pylon_485        | 派能       |
| 12       | Deye(Pylon)_485  | 德业（派能）   |
| 13       | XZH(LCD02)_485   | 鑫智恒(LCD) |
| 14       | GudE_485         | 固德       |
| 15       | NPP-IMB_485      | 视源       |
