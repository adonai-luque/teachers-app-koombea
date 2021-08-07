## This file will have all the commands entered in the terminal during the development of the project

rails new teachers-app-koombea --database=postgresql
rails g scaffold course title:string description:text
rails g scaffold lesson course:references title:string content:text