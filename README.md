# Campaign Manager

Campaign Manager is a frontend Angular application for managing marketing campaigns, connected to a mock backend API.
The app demonstrates modern Angular development patterns using RxJS for state management and reactive programming.

![Create a new compaign](https://github.com/elinechyprenko/ng-campaign-dashboard/blob/master/create_campaign.png)
![Сompaign List](https://github.com/elinechyprenko/ng-campaign-dashboard/blob/master/campaign_list.png)

## 🚀 Features
- **Browse Campaigns**: Display campaigns in a structured table with all key metrics
- **Inline Editing**: Edit campaign details directly in the table with instant save/cancel actions
- **Create Campaigns**: Add new campaigns through a reactive form with validation and balance tracking
- **CRUD Operations**: Full Create, Read, Update, and Delete functionality for campaigns
- **Reactive Architecture**: Built using RxJS BehaviorSubject and Observables for efficient state management

## 🛠️ Technologies Used

### Frontend
- [Angular](https://angular.io/)
- [RxJS](https://rxjs.dev/)

### Backend (Mock API)
- [JSON Server for mock REST API]

## Development server

- Install dependencies for frontend: `npm install`
- Start the mock API server: `json-server --watch db.json --port 3000`.
- Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
