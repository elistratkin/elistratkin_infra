# elistratkin_infra

bastion_IP = 51.250.31.218
someinternalhost_IP = 10.129.0.3

Инфраструктура состоящая из двух машин bastion и someinternalhost поднята на базе Ubuntu 18.06 Bionic. Someinternalhost не имеет публичного ip адреса и доступ к ней осуществляется либо через бастион, либо через vpn на базе pritunl

*Знакомство с облачной инфраструктурой. Yandex.Cloud*
**Самостоятельное задание**
Исследовать способ подключения к someinternalhost в одну команду из вашего рабочего устройства, проверить работоспособность найденного решения и внести его в README.md в вашем репозитории.<br>
Для моего случая это будет <strong>ssh -i ~/.ssh/appuser -A appuser@51.250.31.218 ssh -tt appuser@10.129.0.3</strong>

![Подключение с локальной машины в одну команду](./connect_by_one_command.jpg)<br>
