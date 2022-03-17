# Create a RESTful service with ASP.NET Core controllers that supports create, read, update, delete (CRUD) operations.

</br>INTRODUCTION
</br>This module explores creating a cross-platform RESTful service by using ASP.NET Core web API controllers with .NET and C#.

</br>This module uses the .NET CLI (command-line interface) and Visual Studio Code for local development. After you complete this module, you can apply its concepts by using a development environment like Visual Studio (Windows) and Visual Studio for Mac (macOS). You can also apply the concepts to continued development through Visual Studio Code (Windows, Linux, and macOS).

</br>SUMMARY
</br>In this module, you created an ASP.NET Core web API running on .NET. The web API creates, reads, updates, and deletes pizzas from an in-memory cache.

</br>You learned that creating a web API with ASP.NET Core entails:

</br>Creating a new application by using the ASP.NET Core Web API template.
</br>Creating classes that inherit from the ControllerBase class and that contain methods that respond to HTTP requests.
</br>Because this pattern allows you to focus on a single controller action at a time, with a little practice you can create functional web APIs pretty quickly.

</br>In this module, you used an in-memory cache. This approach helped you to focus on learning web API concepts, but it has some obvious limitations for real-world applications. If the application stops, all your changes are lost!

</br>In a real-world application, you'll want to store your data in a backing store like a database. You can learn how to persist and retrieve relational data by using Entity Framework Core in this tutorial.
