scuola-guida
============

В мене ОС Windows 7 і тут досить проста інсталяція RoR http://railsinstaller.org/
Якщо використовуються Linux ОС, то інсталяція згідно інструкції повинна виглядати наступним чином:
  
  1) Є розписана інструкція http://blog.sudobits.com/2012/05/02/how-to-install-ruby-on-rails-in-ubuntu-12-04-lts/
    Або
  http://ruby.railstutorial.org/ruby-on-rails-tutorial-book#sec-rubygems
  
  2) Після того як встановили RoR створювати проект вже не потрібно, потрібно лише встановити необхідні GEM-и. 
  Їх список знаходиться у файлі Gemfile кореневого каталогу scuola-guida. З часом при потребі можна буде додати інші.
  Отже щоб встановити геми потрібно зайти в каталог scuola-guida і виконати команду:
  
  bundle update
  bundle install
  
  3) Для того, щоб перевірити на працездатність наш проект після ініціалізації необхідно запустити Rails сервер командою:
  
  rails server

  Після цього можемо зайти на http://localhost:3000/ і отримаєм базову сторінку таку як на Heroku
