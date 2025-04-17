# TravelPlanner
📝 Project Description: The Travel Planner is a full-stack web application developed using C# and ASP.NET MVC that allows users to search, plan, and manage their trips seamlessly. The application provides features to search destinations, create itineraries, view weather forecasts, book hotels/activities, and save trip details for future reference.
#🔧 Key Features:
User Authentication: Secure user login and registration system using ASP.NET Identity.

Trip Creation & Management: Users can create, update, and delete trips, including destination, travel dates, budget, and activities.

Itinerary Planner: Drag-and-drop interface to add events like hotel bookings, sightseeing, etc., to each day.

Interactive Maps: Integration with Google Maps API to help users visualize destinations and locate nearby attractions.

Hotel & Activity Listings: Simulated listing of hotels and attractions with filtering options (category, rating, price).

Weather Forecast: Integration with a weather API (like OpenWeatherMap) to show weather info of planned destinations.

Admin Panel: Admins can manage users, destinations, and activities using a dashboard.

Responsive Design: Mobile-first UI built with Bootstrap for access across devices.

#🗃️ Database Design (Sample):
Users (UserId, Name, Email, PasswordHash)

Trips (TripId, UserId, Destination, StartDate, EndDate, Budget)

ItineraryItems (ItemId, TripId, Title, Date, Time, Location, Description)

Destinations (DestinationId, City, Country, ImageUrl, Description)

Activities (ActivityId, DestinationId, Name, Category, Price, Rating)

#✅ Learning Outcome / Highlights:
Developed CRUD operations using ASP.NET MVC and Entity Framework Code First.

Implemented authentication and authorization using ASP.NET Identity.

Used RESTful APIs (Weather, Google Maps) to enrich the app’s functionality.

Practiced real-world MVC architecture and layered development.

Applied responsive UI techniques using Bootstrap and client-side scripting.

