# DiSSCo-Form-Application
Repository for the DiSSCo Form Application

<h3> Usage of the Form Application </h3>

A manual about the use of the DiSSCo Form Application can be found at the following url: https://docs.google.com/document/d/1DAFDgApsmkK4y4Bzjx2ImtiFn_WsaTvh_Do6LlPpMn4/edit#

<h2> General overview </h2>

The Form Application is a simple web-application that allows users to manage DiSSCo related forms in an orderly manner because it links forms and their responses to organisations ROR identifiers. The way it does this is by adding an organisations field to a form. When respondents fill in the form, they will choose their respective organisation, which then is saved within the survey application. Next, when a form is due and the results are ready, they can be exported. During the exportation the Form Application links responses to the organisation’s ROR identifiers and saves them by this identifier in the DiSSCo database. The responses can in the future be used by other services for analysis or visualisation.

The application is built on Google Apps Script, which is an online Javascript editor that supports seamless integration with Google Services (forms, sheets, etc.). The choice has been made to also integrate functionality for the other services (SurveyMonkey) in this editor. The current version of the application can be found at:

https://script.google.com/macros/s/AKfycbxyrQTvszdMh5nhtlQuj0aJHLVjXmhHvBQGse-T2alaNpVxMWFreSDSUMs2lWeZOZcf/exec    

In order to be able to use the app, you will need to login with a Google Account.

In preparation of the Form Service, please follow the required configuration steps for SurveyMonkey when making use of this functionality.
