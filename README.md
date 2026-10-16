## Setup Instructions

1. **Prerequisites:** .NET 8 SDK, SQL Server (or LocalDB), Git
2. **Clone:** `git clone https://github.com/YourUsername/RaceDay-API.git`
3. **Database:** Update `appsettings.json` connection string if needed
4. **Apply Migrations:** `dotnet ef database update`
5. **Run:** `dotnet run --project RaceDay.API`
6. **Swagger:** Navigate to `https://localhost:{port}/swagger`

   2 role description
   ## Roles

### Organiser
- Create, update, and delete events
- Define categories (age/distance) for events
- View enrollments for their events
- Capture results (finish time, position) for participants

### Participant
- View all events and categories
- Enroll in events by selecting a category
- View their own results
