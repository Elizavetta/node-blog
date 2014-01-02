# Примерный план лекций

1. Основы NodeJS
     - Философия NodeJS: низкоуровневось, модульность, однопоточность. (Отличия от ClientSide JS)
     - Глобальные объекты: global, process, module, Buffer.
     - Возможности NodeJS: системные утилиты, CLI, серверы, … (Надо подумать еще)
     - NPM, установка пакетов, создание своих пакетов, публикация пакетов
2. Express общий обзор
     - Настройка
     - .use()
     - middlewares
     - шаблонизаторы
     - .param() 
     - css-препроцессоры
     - .router()
     - middlewares в рамках роутера.
     - req, res
3. Пишем блог
     - Страница «пост»
     - Страница «список постов» 
     - Авторизация (apache basic-auth)(кнопки «редактоировать/удалить» будут видны только авторизованному пользователю)
     - Страница редактирования/написания поста (textarea + markdown) 
     - mongodb