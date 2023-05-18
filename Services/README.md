# Vimo Services


| Number | VPS | Name | Services | RAM (current) | Dev | Hardware | Configurations path - NginX Proxy |
| :---: | :---: | :---: | :---: | :---: | :---: | :--- | :--- |
| 1 | yy.xx.xx.xx | vimo-api01-xx-xx | vimo-notify | 350MB | 2GB | CentOS <br/> 8CPU <br/> 8GB RAM <br/> 10GB data OS <br/> 150GB data | http://yy.xx.xx.xx:xxxx/notify |
| 2 |  |  | vimo-notify |	400MB |	2GB |  | http://yy.xx.xx.xx:8960/media |
| 3 | yy.xx.xx.xx | vimo-api02-xx-xx	| vimo-payment | 660MB | 2GB | CentOS <br/> 16CPU <br/> 28GB RAM <br/> 10GB data OS <br/> 200GB data | http://10.0.36.41:8940/payment |
| 4 |  |  | vimo-checkout | 462MB |	2GB |  | http://yy.xx.xx.xx:8940/checkout |
| 5 |  |  | vimo-backend | 700MB |	3GB |  | http://yy.xx.xx.xx:8940/backend |
| 6 |  |  | vimo-wallet | 620MB |	2GB | |  | http://yy.xx.xx.xx:8940/wallet |
| 7 |  |  | vimo-merchant | 2.8GB |	4GB |  | http://yy.xx.xx.xx:8940/merchant |
| 8 |  |  | vimo-VAS | 940MB | 2GB |  | http://yy.xx.xx.xx:8940/vas |
| 9 |  |  | vimo-user | 640MB | 2GB | | http://yy.xx.xx.xx:8940/user |
| 10 | yy.xx.xx.xx | vimo-api03-xx | vimo-backend | 2.2GB | 3GB | CentOS <br/> 8CPU <br/> 8GB RAM <br/> 10GB data OS <br/> 70GB data | 1. http://yy.xx.xx.xx:8930/backend/accountant-report <br/> 2. http://yy.xx.xx.xx:8930/backend/service-req-payout/rest/ <br/> 3. http://yy.xx.xx.xx:8930/backend/service-tranfer-req/rest/ <br/> 4. http://yy.xx.xx:8930/backend/payment-cash-out/rest/excel/v2 <br/> 5. http://yy.xx.xx.xx:8930/backend/payment-cash-in/rest/excel/v2 <br/> 6. http://yy.xx.xx.xx:8930/backend/accountant-report/monthly |


<!--
<table>
    <thead>
        <tr>
            <th>Layer 1</th>
            <th>Layer 2</th>
            <th>Layer 3</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=4>L1 Name</td>
            <td rowspan=2>L2 Name A</td>
            <td>L3 Name A</td>
        </tr>
        <tr>
            <td>L3 Name B</td>
        </tr>
        <tr>
            <td rowspan=2>L2 Name B</td>
            <td>L3 Name C</td>
        </tr>
        <tr>
            <td>L3 Name D</td>
        </tr>
    </tbody>
</table>
-->
