# Laravel Destination Finder test project

![Thumbnail](https://repository-images.githubusercontent.com/590404206/f7017d0c-1741-4e05-b805-7123dd47be40)

You have buses driving routes with specified stops. Each route have multiple stops and each stop might multiple routes driving through it. The stops for a specified route have a specific order.

Imagine we have the following routes defined:

- Tallinn-Haapsalu with stops: Tallinn, Saue, Keila, Riisipere, Haapsalu
- Haapsalu-Tallinn with the same stops in a reverse order
- Tallinn-Tartu with stops: Tallinn, Kose, Paide, Põltsamaa, Tartu
- Tartu-Tallinn with the same stops in a reverse order

If a person would be at a Saue stop then s/he could directly only travel to stops on Tallinn-Haapsalu or Haapsalu-Tallinn routes which come after Saue stop. S/he can travel to Riisipere but not to Kose.

This should provide you enough context when building the API.

You can find models, migrations, seeders, etc in this repository which you can copy to your scaffolded Laravel project.

## Tasks

Create a Laravel application with the feature below.

### API

- Create endpoint to fetch all Stops
- Add possibility to the same endpoint to get available destinations from a given stop
- Use as few SQL queries as possible
- Check if all approapriate indexes are created

## Submission

Create a Git repository and share the link or access to our CTO - Allan (allan@outl1ne.com).