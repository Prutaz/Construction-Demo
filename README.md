Hands Out Build Group
Hands Out Build Group is a Razor Pages web application designed to showcase a construction company's services, projects, blog posts, and contact information. The application is built using ASP.NET Core Razor Pages and targets .NET 8.

Table of Contents
├── Features
├──Project Structure
├── Pages Overview
├── Technologies Used
├── Setup Instructions
├── License
Features
├──Responsive Design: Fully responsive layout using Bootstrap.
├──Dynamic Content: Razor Pages for dynamic content rendering.
├──Hero Section: Engaging hero carousel on the homepage.
├──Services: Detailed services offered by the company.
├──Projects: Showcase of completed projects with filtering options.
├──Blog: Recent blog posts with detailed pages.
├──Contact Form: Functional contact form for user inquiries.
├──SEO Optimized: Meta tags and structured content for better search engine visibility.

Project Structure
HandsOutBuild/
├── Pages/
│   ├── About.cshtml
│   ├── Blog.cshtml
│   ├── Blog-Details.cshtml
│   ├── Contact.cshtml
│   ├── Index.cshtml
│   ├── Project.cshtml
│   ├── Project-Details.cshtml
│   ├── Services.cshtml
│   └── Shared/
│       └── _Layout.cshtml
├── wwwroot/
│   ├── assets/
│   │   ├── css/
│   │   ├── img/
│   │   ├── js/
│   │   └── vendor/
│   └── lib/
├── appsettings.json
└── Program.cs
                    
Pages Overview
1. Index.cshtml (Home Page): Hero section with a carousel, overview of services, projects, and testimonials.

2. About.cshtml: Information about the company and its mission.

3. Services.cshtml: Detailed list of services offered by the company.

4. Project.cshtml: Gallery of completed projects with filtering options.

5. Project-Details.cshtml: Detailed view of a specific project.

6. Blog.cshtml: List of recent blog posts.

7. Blog-Details.cshtml: Detailed view of a specific blog post.

8. Contact.cshtml: Contact form for user inquiries and company contact details.

9. Shared/_Layout.cshtml: Shared layout for consistent header, footer, and navigation across all pages.

Technologies Used
ASP.NET Core Razor Pages: For server-side rendering.
Bootstrap: For responsive design and styling.
AOS (Animate On Scroll): For scroll animations.
Swiper.js: For carousels and sliders.
Isotope.js: For project filtering.
FontAwesome: For icons.
Setup Instructions
Clone the Repository:
git clone https://github.com/your-repo/hands-out-build-group.git
cd hands-out-build-group
                            
Install Dependencies:
dotnet restore
                            
Run the Application:
dotnet run
                            
Access the Application: Open your browser and navigate to http://localhost:5000.
Publish the Application (Optional):
dotnet publish -c Release -o ./publish
                            
License
This project is licensed under the MIT License. See the LICENSE file for details.
