# CS-340
Client Server Development

# How do I approach designing software?

Writing maintainable code really comes down to keeping things organized and modular. The CRUD module from Project One is a perfect example of this. By putting all the database operations into one dedicated file, I didn’t have to mix database logic with dashboard logic in Project Two. That separation made the dashboard easier to build, easier to debug, and easier to update later. If the database structure ever changes, I only need to adjust the CRUD module instead of digging through multiple files. This approach also makes the modular reusable. I could plug it into future dashboards, automation scripts, or any project that needs MongoDB access. Clean structure, clear naming, and consistent functions go a long way in keeping code adaptable.

# How do I approach developing programs?

For Grazioso Salvare’s requirements, I approached the project by breaking everything into small, manageable steps. First, I made sure I understood the data and what the client actually needed. Then I built the CRUD operations, tested them, and only after that did I connect the dashboard widgets. This felt more like real client work compared to earlier courses, where assignments were smaller or more guided. Here, I had to think about how the pieces fit together, how the data flows, and how to keep the structure clean. In future projects, I’d use the same strategy: start with understanding the data, plan the architecture, build modular components, and test each part before combining them. It keeps the project organized and reduces headaches later.

# How can computer science help me in reaching my goals?

Computer scientists solve problems by building tools that help people work more efficiently and make better decisions. A dashboard like the one in this project is a good example. It turns raw data into something interactive and useful. Instead of manually searching through records, a company like Grazioso Salvare can quickly filter dogs, visualize trends, and identify candidates for rescue training. This kind of work matters because it directly supports their mission and proves how they operate day-to-day. Good software saves time, reduces errors, and helps organizations focus on what they do best.
