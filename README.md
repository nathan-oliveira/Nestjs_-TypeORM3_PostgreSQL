nest g resource modules/users --dry-run

nest g resource modules/users

docker run --name postgres -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres

# para dar permisão de execução
chmod +x .docker/entrypoint.sh

# executar comando dentro do docker
docker-compose exec app pwd
docker-compose exec app bash
npx typeorm migration:create -n CreateCoursesTable

exit

docker-compose ps
docker-compose stop
docker-compose down

docker-compose up

## TypeORM 3

npx typeorm migration:create src/migration/CourseRefactoringTest
yarn build && npx typeorm migration:run -d dist/database.providers.js



npm run test --courses.service

