JobsApp
=======

Запуск: 
   * Перейти в директорию docker
   * Собрать контейнеры: docker-compose build
   * Запустить: docker-compose up -d

Приложение доступно на порту 5000. 
Поддерживает отображения списка вакансий: api/vacancies
Есть поиск по названию и зарплате: GET api/vacancies?name=interesting_name&&salaryFrom=50000
