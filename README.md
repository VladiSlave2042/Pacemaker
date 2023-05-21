# "Pacemaker" "Бойко Владислав"

---

## Задание 1

Pacemaker — это менеджер ресурсов кластера со следующими основными фичами:
    1. Обнаружение и восстановление сбоев на уровне узлов и сервисов;
    2. Независимость от подсистемы хранения: общий диск не требуется;
    3. Независимость от типов ресурсов: все что может быть заскриптовано, может быть кластеризовано;
    4. Поддержка STONITH (Shoot-The-Other-Node-In-The-Head) — лекарства от Split-Brain ;
    5. Поддержка кластеров любого размера;
    6. Поддержка и кворумных и ресурсозависимых кластеров;
    7. Поддержка практически любой избыточной конфигурации;
    8. Автоматическая репликация конфига на все узлы кластера;
    9. Возможность задания порядка запуска ресурсов, а также их совместимости на одном узле;
    10. Поддержка расширенных типов ресурсов: клонов (запущен на множестве узлов) и с дополнительными состояниями (master/slave и т.п.);
    11. Единый кластерный шелл (crm), унифицированный, скриптующийся.
    12. Поддержка heartbeat и corosync

Основное назначение - создание HA кластеров

---

## Задание 2

Corosync - реализует систему группового общения для отказоустойчивых кластеров. Такой себе агент внутри кластера, что то вроде zabbix агента в смети с rabbitmq. Не является самомтоятельной софтиной, а прибывает в качестве связующего узла в управлении кластерами высокой доступности.

1. Следит за состоянием приложения;
2. Оповещает приложение о смене активной ноды;
3. Отправляет одинаковые сообщения процессам на всех узлах кластера;
4. Предоставление доступа к БД с конфигом и статистикой, а так же отправка уведомлений о ее измерениях.

---

## Задание 3

---

## Задание 4
