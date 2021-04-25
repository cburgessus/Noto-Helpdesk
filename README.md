# Noto-Helpdesk
A flexible help desk to help your techs stay organized and resolve faster.

## Project Planning

### Stack Requirements

- A tier 2 or tier 3 Distributed SQL Network
- Graphical User Interface
- Command Line Interface
- C#
- .NET Framework
- HTML5, Javascript, and CSS
- Bootstrap
- Java
- Visual Studio For Windows
- Android Studio
- Git

### Feature Overview

- **Two-Factor Log-In Authentication Form**: To start using Noto, you'll be presented with a log-in and registration form. If you're a returning user, you can enter your email and password, and alternatively, choose to remember your credentials on this device. If you're a new user, you'll enter your email, password, password hint, and two factor authentication before registering. You'll get an email notification when you're account is created. 
- **Company Selection Form:** After you log in, Noto will show you all the companies you have access to. You can click a company's title card to access the that company's help desk. Alternatively, you can always add a company on this screen.
- **Add Company:** If you need to add a company, Noto will ask if you'd like to join an existing company or start a new company. 
- **Joining A Company:** If you're joining an existing company, you'd enter the unique company ID given to the company administrators. Then you'd press the Join button to be added to the company's Join List. Company Administrator will get notified that you'd like to join and one of them will approve you. You'll get notified that you're trying to join a company, and when an administrator approves you.
- **Creating A Company:** If you're starting a new company, you'll assign the company a name and  you'll select how many seats you want for your company. The first 5 seats will be free, but anything after that will be charged at a yearly fee.
- **Payment Collection:** If you're buying seats, you'll be asked to provide payment information to start your subscription. After the payment is processed, Noto will create your helpdesk and you'll receive a receipt of your purchase with the unique company ID and you'll be able to access your company's help desk.
- **End-To-End Encryption**: Every piece of information sent to the database or payment center is encrypted to help keep prying eyes at bay.
- **Virtual Tour:** Once you log into your helpdesk for th first time, Noto will walk you through how to use everything. Noto will give you access to Tickets, Notifications, Spam Prevention, Auto-Replies, Templates, A Knowledge Base, Transcription Tools, Import/Export Tools, and Tracking Tools.
- **Notifications**: To help you stay on top of your notifications, Noto will let you choose how you want to get notified of things happening in your help desk. You'll be able to receive emails, sms, desktop notifications, push notifications, and web notifications. A log will automatically track everything for you.
- **Spam Prevention**: To help you prevent spam, we've implemented Captcha Codes, Wildcard Blocking, and Limited Entry uses. 
- With **Wildcard Blocking**, you can block IP addresses, usernames, emails, domains, ticket subjects, and ticket summaries that meet criteria you specify. These tickets never get through to your database.
- With **Limited Entry** uses, you can determine how many requests a user can fill out a ticket per interval of time. By default, your users can submit 3 tickets per 30 minutes. After your user reaches the maximum allowed tickets, the server won't accept any new entry from the user until after the timer elapses.
- **Knowledge Base**: Save your employees and clients time and money by filling out forms outlining repetitive questions. Each knowledge base article will be easily searchable and updatable so everyone has the latest information about a given problem or solution.
- **Auto-Replies:** Once you get your knowledge base filled, you can set up your tickets to automatically reply to commonly asked questions. You can set up your tickets to greet the client and refer them to the appropriate knowledge base article.
- **Note Upload**: We've given your employees the ability to upload notes in a format that works best for them. Your employees can add images, image scans, videos, audio, and URLs to your knowledge base.
- **Note Transcription**: You want your notes to be fast though and sometimes people want a searchable copy that they can print on their own. Regardless of your note taking strategy, Noto will convert your notes into searchable text. Noto will use OCR to convert your handwritten notes, and audio transcription to convert your videos and audio clips. 
- **Custom Fields**: Each helpdesk will support custom ticket fields to help you collect and organize data that matters to you. Don't worry, only administrators can add modify the custom fields.
- **User Authorization**: Set roles and rules for each of your employees. By default, your employee can be an administrator, moderator, technician, contributor, or end user.
- **Auto Assign**: In addition to the rules you set for each of your employees, you can also set ticket rules to automatically assign a ticket to one of your employees. Your employee and the end user will get notified whenever their ticket is created and assigned. 
- **Tracking**: Learn how much time is spent on each ticket, and set up goals to help make sure everyone exceeds your expectations.  
- **Ticket Status**: Depending on the roles set in your help desk, certain roles will be able to open, close, or pend tickets. Your employee and the client will be notified whenever the ticket status changes.
- **Bulk Control Tickets**: With the bulk control tools, you'll be able to import, export, and modify many tickets with one action.
- **Out Of The Box Setup**: There's minimal configuration needed to get the help desk running. We take care of it all for you.
- **Backup Ready**: We'll automatically backup your help desk to help you protect your work.
- **Server Redundancy**: We can't promise that outages won't happen, but if they do, we implemented ways to keep your helpdesk running through the outages.
- **Server Status Page**: To help you know if we're experiencing an outage, you can visit our server status page to see if the server is down for any reason.
- **User Configurable**:  For people who want more control over the help desk, we tried to make every setting configurable in your settings. If you require more control, send us a help desk ticket and we'll be happy to see what we can do.

### Design

Noto is supposed to work on various devices. Since we'll be supporting devices of different sizes, we need to create a universal interface. The universal interface takes a mobile-first approach. We'll design Noto around the minor interface and scale it to fit more extensive interfaces. Our users will always have access to all the information they need, and they'll always have a familiar experience.

## Development

## Testing

## Integration

## Deployment

## Maintenance