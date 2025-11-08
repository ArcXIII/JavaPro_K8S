# Задание №3 по курсу JavaPRO Модуль 2

## Задача 1

K8S развёрнут на базе Docker Desktop

## Задача 2

Подготовлен манифест пода: [Манифест](task3/task-2-simple-pod.yaml)

## Задача 3

Манифест применён, под запущен: [Результат выполнения манифеста](task3/task-3-simple-pod-deployment-result.yaml)

## Задача 4

### Удаление пода
До удаления: <br> ![Существует](task3/task-4.png)

После удаления: <br> ![Удалён](task3/task-4-pod-deleted.png)

## Задача 5

Деплоймент: [Манифест](task3/task-5-deployment-and-svc.yaml)

Результат: <br> ![Результат](task3/task-5-results.png)

## Задача 6

Результат теста запущенного через деплоймент приложения: <br> ![Результат](task3/task-6-app-test.png)

## Задача 7

Удаляем под, ожидаем, что создастся новый

До: <br> ![Результат](task3/task-7-1.png)

После: <br> ![Результат](task3/task-7-2.png)

## Задача 8

Масштабирование до 3 реплик и обратно на 1

Replica count = 3: <br> ![Результат](task3/task-8-1.png)

Replica count = 1: <br> ![Результат](task3/task-8-2.png)
## Задача 9

Обновление версий образа в деплойменте

До: <br> ![Результат](task3/task-9-1.png)

После: <br> ![Результат](task3/task-9-2.png)

# Задание №4 по курсу JavaPRO Модуль 2

## Задача 1

Манифест: [1. daemon-set.yaml](task4/1.%20daemon-set.yaml)

Результат:

![1.1.png](task4/1.1.png)

![1.2.png](task4/1.2.png)

## Задача 2

Манифест: [2. stateful-set.yaml](task4/2.%20stateful-set.yaml)

Результат:

![2.1.png](task4/2.1.png)

![2.2.png](task4/2.2.png)

## Задача 3
Манифест: [3. job.yaml](task4/3.%20job.yaml)

Результат: 

![3.png](task4/3.png)

## Задача 4
### 4.1

Манифест: [4.1. cronjob.yaml](task4/4.1.%20cronjob.yaml)

Результат: 

![4.1.png](task4/4.1.png)

### 4.2

Манифест: [4.2. second cronjob.yaml](task4/4.2.%20second%20cronjob.yaml)

Результат:

![4.2.png](task4/4.2.png)

### 4.3

kubectl create job --from=cronjob/cronjob-test-2 manual-job-from-cronjob-2

Результат:

![4.3.png](task4/4.3.png)