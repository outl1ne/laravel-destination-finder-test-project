# Laravel Destination Finder test project

![Thumbnail](https://repository-images.githubusercontent.com/590404206/f7017d0c-1741-4e05-b805-7123dd47be40)

You have buses driving routes with specified stops. Each route has multiple stops and each stop might be a part of many different routes. The stops which make up a route have a specific order.

Imagine the following routes:

- Tallinn-Haapsalu with stops: Tallinn, Saue, Keila, Riisipere, Haapsalu
- Haapsalu-Tallinn with the same stops in reverse order
- Tallinn-Tartu with stops: Tallinn, Kose, Paide, Põltsamaa, Tartu
- Tartu-Tallinn with the same stops in reverse order

If a person is at Saue stop then they can only travel to stops on Tallinn-Haapsalu or Haapsalu-Tallinn routes which come after Saue stop in the direction of the route (in case of Tallinn-Haapsalu route, they can travel to Keila, but not Tallinn).

This should provide you enough context when building the API.

You can find models, migrations and seeders in this repository. You are free to copy them to your scaffolded Laravel project.

## Tasks

Create a Laravel application with the following features.

### API

- Create an API endpoint to fetch all stops
- Add an option to the same endpoint to get all available destinations from a given stop
- Use as few SQL queries as possible
- Check if all appropriate indexes are created

## Submission

Create a Git repository and share the link or access to our CTO - Allan (allan@outl1ne.com).
