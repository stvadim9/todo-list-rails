# Rails Комманді
Это сводка команды Rails, используемой для генерации веб-страницы.

        $ rails _5.0.2_ new rails-to-do
        $ rails g scaffold todo_list title:string description:text
        $ rails db:migrate
        $ rails g model Todo_item content:string todo_list:references
        $ rails db:migrate
        $ rails g controller todo_items
        $ rails g migration add_completed_at_to_todo_items completed_at:datetime
        $ rails db:migrate
