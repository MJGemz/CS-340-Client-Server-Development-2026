# CS-340-Client-Server-Development-2026

How I Write Maintainable, Readable, and Adaptable Code

When I write code now, I think a lot more about how it’s going to look later, not just whether it works in the moment. Earlier on, I used to just focus on getting the output, but in this course I started organizing things better and separating responsibilities.

A good example of that is my CRUD Python module. Instead of putting my MongoDB connection and queries directly inside the dashboard, I created a separate file just for database operations. At first, it felt like extra work, but it ended up saving me a lot of time. When I moved into Project Two, I didn’t have to rebuild anything. I just reused the same module and plugged it into my dashboard.

This also helped when I ran into problems. There were times where my dashboard wasn’t showing data or my queries weren’t working, and because my code was separated, I could test the database part on its own. That made debugging way easier and less confusing.

Going forward, I can reuse this same CRUD module in other projects. For example, if I build a healthcare system or anything related to Health IT, I already have a starting point for handling data. I can also expand it by adding update and delete features or more advanced queries. It’s something I can keep building on instead of starting from scratch every time.

How I Approach Problems as a Computer Scientist

My approach to solving problems has definitely improved during this project. Instead of trying to do everything at once, I started breaking things down into smaller steps and focusing on one piece at a time.

For this dashboard, I didn’t jump straight into building everything. I started with the database connection, then made sure I could read data. After that, I built the data table, then added filtering, then worked on the chart, and finally the map. There were times where things didn’t work, especially with the map and filters, but because I built everything step by step, I knew where the issue was coming from.

This project felt more real compared to other assignments I’ve done. It wasn’t just about writing code to answer a question. I had to think about how a user would interact with the dashboard and how everything connects together. I also had to test everything as I went, instead of waiting until the end.

One thing I’ll keep doing in the future is testing each part before moving on. That helped me avoid bigger problems later. I also learned that it’s okay to go back and fix things instead of trying to force everything to work at once.

What Computer Scientists Do and Why It Matters

Before this project, I thought of programming mostly as just writing code, but now I see it more as building tools that help people do their jobs better. Computer scientists take data and turn it into something useful and easy to understand.

With this dashboard, I created something that could actually help a company like Grazioso Salvare. Instead of going through raw data, they can filter animals, see patterns in charts, and even view locations on a map. That saves time and makes their work more efficient.

This kind of work matters because a lot of organizations rely on data, but without the right tools, that data can be overwhelming or hard to use. By building systems like this, we make it easier for people to make decisions and take action.

For me personally, this project connects a lot to what I want to do in Health IT. Hospitals and healthcare systems also deal with large amounts of data, and they need tools to manage it. The skills I learned here, like working with databases, building dashboards, and organizing code, are things I can apply directly in that field.
