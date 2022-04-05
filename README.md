# Postman!
![image](https://user-images.githubusercontent.com/97470160/161740068-3939368b-4f74-4a2d-a738-181620961835.png)


Что бы понять его уходит не так мало времени, но скажу честно, это затягивает.
Изучили написание тестов в Постмане, его синтаксис, отправление запросов, создание #environment, передача в окружение переменную.
Что поняли, и сделали:
- Отправляли запрос. Статус код 200
- Спарсили response body в json в GET и POST
- Спарсили request в GET и POST
- Проверяли, что параметр в ответе равно параметру в  request (этот параметр забрать из request.) с помощью pm.expect().to.eql()
- Выводили в консоль параметры из request. с помощью console.log
- Создали в окружение переменную через сниппет pm.environment.set
-написали цикл который выведет в консоль по порядку элементы списка из параметра с помощью команды
- Проверяли, что json response имеет параметры, это команда to.have.property
проверку структуры json в ответе;
- передавали переменную
через окружение в следующий запрос;
- брали любой объект из списка, используя js random;
- писали тесты по проверке правильности результата
перемножения на коэффициент с помощью     pm.expect(..).to.have.to.eql(..);
- проверили, что один элемент массива больше или меньше другого с помощью (above и below)

# Ссылки на видео моих работ 

[<img align="left" alt="RomanovaValentina | LinkedIn_1" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin1]
[<img align="left" alt="RomanovaValentina | LinkedIn_2" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin2]

<br />

[linkedin1]: https://www.linkedin.com/posts/valentina-romanova-1b948922a_postman-environment-activity-6892750800066871296-gzAf?utm_source=linkedin_share&utm_medium=member_desktop_web
[linkedin2]: https://www.linkedin.com/posts/valentina-romanova-1b948922a_postman-testing-qa-activity-6895035013692235777-VdnE?utm_source=linkedin_share&utm_medium=member_desktop_web
