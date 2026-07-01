# Law Firm Nouf Alzahrani

Arabic Razor Pages website for Nouf Alzahrani Law and Notary Office. The project presents a polished public website for legal and notary services, with Arabic RTL layout, service pages, blog content, contact actions, and responsive styling.

## Preview

![Nouf law firm website preview](wwwroot/images/hero-law-office.png)

## Highlights

- Arabic-first website with RTL layout and responsive design.
- ASP.NET Core Razor Pages architecture using .NET 10.
- Homepage hero carousel with legal/notary service calls to action.
- Services page covering legal consultations, contracts, disputes, business support, compliance, and notary services.
- Blog page with Arabic legal articles and client-side search/filtering.
- Contact actions for WhatsApp, email, phone, and Google Maps location.
- Bootstrap integration with custom CSS and branded visual assets.
- SEO basics: page titles, description metadata, favicon, and indexable pages.

## Tech Stack

| Layer | Technology |
| --- | --- |
| Web App | ASP.NET Core Razor Pages, C#/.NET 10 |
| Frontend | HTML, CSS, Bootstrap, JavaScript |
| Assets | Static images and branded website media |
| Tooling | .NET CLI, Git, GitHub |

## Repository Structure

```text
Pages/                    Razor Pages for home, services, blog, layout, and shared UI
wwwroot/                  Static CSS, JavaScript, images, favicon, and frontend assets
Properties/               Launch settings
NoufLaw.Web.csproj        ASP.NET Core project file
Program.cs                Application startup and Razor Pages routing
appsettings.json          App configuration
```

## Pages and Features

### Home

- Branded Arabic hero carousel.
- Office introduction section.
- Social media links.
- Legal/notary service routing cards.
- Blog previews.
- Contact section with email, WhatsApp, and maps links.

### Services

- Legal services section for consultations, contracts, letters, claims, disputes, document review, and compliance.
- Business services section for company setup, governance, policies, negotiations, and ongoing legal support.
- Notary services section for powers of attorney, acknowledgements, contracts, companies, and transfers.
- FAQ section for common client questions.

### Blog

- Arabic legal awareness articles.
- Categories covering commercial law, notary work, companies, civil obligations, evidence, regulations, settlements, and compliance.
- Client-side search for filtering posts by topic.

## Run Locally

### Prerequisites

- .NET 10 SDK

### Start the website

```powershell
dotnet run --project NoufLaw.Web.csproj
```

Open the local URL printed by the .NET CLI, usually one of:

```text
http://localhost:5000
https://localhost:5001
```

## Build

```powershell
dotnet build NoufLaw.Web.csproj
```

## Portfolio Notes

This project is useful as a front-end and Razor Pages portfolio piece because it shows Arabic RTL presentation, service-based information architecture, responsive visual design, static asset organization, and simple JavaScript interaction without needing a database-backed admin system.
