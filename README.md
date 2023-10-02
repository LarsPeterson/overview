# Overview 2023

## Artificial Intelligence

- MidJourney

## Project Planning

- [Miro](https://miro.com) is the online collaborative whiteboard platform that enables distributed teams to work effectively. _(free up to 3 boards)_
- [LucidChart](https://www.lucidchart.com) is a online diagramming tool that allows visual collaboration on charts and diagrams. _(free up to 3 documents)_
- [HelloNext](https://hellonext.co) lets you centralize, organize, and respond to customer feedback in one place. _(free up to 2 boards)_

## MacOS 

### [ZSH](https://github.com/ohmyzsh/ohmyzsh) Setup

- .zprofile
  
  ```
  # Default
  
  export PATH="${PATH}:/usr/local/bin"
  
  # NVM (Node Version Manager)
  
  source ~/.nvm/nvm.sh
  
  # Python 3.10
  
  export PATH="${PATH}:/Library/Frameworks/Python.framework/Versions/3.10/bin"
  alias python=python3 # Add Alias for Python 3.10
  
  # Visual Studio Code
  
  export PATH="${PATH}:/Applications/Visual Studio Code.app/Contents/Resources/app/bin"
  
  # Chruby
  
  source /usr/local/share/chruby/chruby.sh
  source /usr/local/share/chruby/auto.sh
  chruby ruby-3.1.2
  ```

## Code Standards

- [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

## Code Environments

- CodePen
- StackBlitz

## Code Trends

- Edge Computing
- ChatGPT
- Containers
- Microfrontends
- Full Stack Frameworks
- Low Code / No Code

## Code Monitoring and Linting

- Sentry
- ReleaseHub
- CodeSee

## Version Tracking

- [Git](https://github.com)

  ```
  git config --list
  git config --global user.name "John Doe"
  git config --global user.email johndoe@example.com
  git stash pop
  git stash pop stash@{0}
  git stash apply
  git stash apply stash@{0}
  ```

## Web Hosting

- Surge
- Fly.io
- Vercel
- Netlify
- Render
- Railway
- Deta.sh
- GitLab Pages
- GitHub Pages
- Cloudflare Pages
- Firebase
- DigitalOcean
- Microsoft Azure ⭐
  - **Azure App Service** for backends, serverside apps.
  - **Azure Static Web App** for JavaScript, clientside apps.
  - [Securing Requests in FrontDoor](https://docs.microsoft.com/en-us/azure/frontdoor/front-door-security-headers)
  - [Logging and Diagnostics](https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/diagnostic-settings?tabs=portal#create-in-azure-portal)
  - Microsoft Power BI
- Amazon AWS
  - [aws-nuke](https://github.com/rebuy-de/aws-nuke) is a great tool for destroying everything in your account.
- Google Cloud

## Web Development

### UI

- [Material UI](https://material.angular.io) is a UI component library used for hastening the development process. _(free)_
- [PrimeNG](https://www.primefaces.org/primeng-v11-lts) is a collection of rich UI components for Angular. _(free)_
- [Bootstrap](https://getbootstrap.com) is a free and open-source CSS framework directed at responsive, mobile-first front-end web development. _(free)_
- [Wijmo](https://www.grapecity.com/wijmo) is a massive frontend **library** that contains everything you need. _($549/developer/year)_

### UI Data Visualization

- [D3.js](https://d3js.org) is a **library** for producing dynamic, interactive data visualizations. _(free)_
- [ThreeJS](https://threejs.org) is a **WebGL engine** that can run GPU-powered games and other graphics-powered apps straight from the browser. _(free)_

### Frameworks

- [RazzleJS](https://razzlejs.org) is a **framework** that abstracts all the complex configuration needed for SSR into a single dependency. _(free)_
- [Tauri](https://tauri.app) is a **framework** with a Rust backend for building tiny, blazingly fast binaries for all major desktop platforms. _(free)_
- [Angular](https://angular.io) is a **framework** for building single-page client applications with TypeScript. _(free)_

### Libraries

- [Lodash](https://lodash.com) is a utility **library** and is the better version of [UnderscoreJS](https://underscorejs.org). _(both are free)_
- [RxJS](https://rxjs.dev) is a reactive **library** using observables that makes it easier to compose asynchronous code. _(free)_
- [React](https://reactjs.org) is a **library** for building component-based interactive UIs. _(free)_

### C#

- [SPA](https://learn.microsoft.com/en-us/aspnet/core/client-side/spa-services?source=recommendations&view=aspnetcore-6.0)
- [Worker Services](https://learn.microsoft.com/en-us/dotnet/core/extensions/workers)
- [WCF Web Service](https://learn.microsoft.com/en-us/dotnet/core/additional-tools/wcf-web-service-reference-guide)
- [ServiceStack](https://servicestack.net)
- Web APIs Part 1: [Creating Discoverable HTTP APIs with ASP.NET Core 5 Web API](https://devblogs.microsoft.com/dotnet/creating-discoverable-http-apis-with-asp-net-core-5-web-api/)
- Web APIs Part 2: [Open-source HTTP API packages and tools](https://devblogs.microsoft.com/dotnet/open-source-http-api-packages-and-tools/)
- Web APIs Part 3: [Generating HTTP API clients using Visual Studio Connected Services](https://devblogs.microsoft.com/dotnet/generating-http-api-clients-using-visual-studio-connected-services/)
- Web APIs Part 4: [App Building with Azure API Management, Functions, Power Apps, and Logic Apps](https://devblogs.microsoft.com/dotnet/app-building-with-azure-api-management-functions-power-apps-and-logic-apps/)

### Java

- https://spring.io/

### Ruby

- [Best Way to Install Ruby on Mac 1](https://stackoverflow.com/questions/51126403/you-dont-have-write-permissions-for-the-library-ruby-gems-2-3-0-directory-ma)
- [Best Way to Install Ruby on Mac 2](https://mac.install.guide/ruby/12.html)

## Web Testing

- [Spelling Check](https://datayze.com/website-spell-checker)
- [Contrast Checker](https://coolors.co/contrast-checker)

## Game Development

- [Unity3D](https://github.com/LarsPeterson/unity3d)
  - https://assetstore.unity.com/packages/tools/utilities/build-report-tool-8162
  - https://assetstore.unity.com/packages/tools/utilities/asset-hunter-pro-135296
  - https://github.com/Siccity/GLTFUtility
  - Methods of Movement
    - Rigidbody SetVelocity
    - Rigidbody MovePosition
    - Rigidbody AddForce
    - Transform Translate
    - Transform Set Position

- [Godot](https://godotengine.org/) ⭐

## Game Art

- [OpenGameArt](https://opengameart.org/)
- [Itch.io](https://itch.io/game-assets/free)

## Game Art Tools

- https://ezgif.com/sprite-cutter/

## 3D Modeling

- [Blender](https://www.blender.org/)
- [TinkerCad](https://www.tinkercad.com/)
- [Mixamo](https://www.mixamo.com/)

## Graphic Design

- Adobe Photoshop ⭐
- Canva ⭐
- LottieFiles
(https://lottiefiles.com)

## UI/UX

- Figma
- Adobe XD ⭐

## Electrical

- [Fritzing](https://fritzing.org/)
