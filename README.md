# I'm Just a Salon App

### This app is for my mom so it's simple and open source for evereyone. 😉

Basicly is a **"Self-hosted web app"**, It has a front end that connects to the back end through RESTful APIs, all locally.

## Why problem my app solve?

Solve_01 --> High cost with other programs that "overkill" my needs.

Solve_02 --> Programs with poor UI x UX.

Solve_03 --> Lack of basic integration with WhatsApp for scheduling appointments.

Solve_04 --> Solutions that are not easily customizable.

## Who are the users?

The user will be unique per system (at least for now), and will manage all their salon activities through the app.

## What does the user need to do?

He needs to be able to manage his salon operations in a basic way.

## Let's go to UC's!

Entity --> Clients

    - FR_01: The system should allow the user to create clients using name, e-mail and phone number
    - FR_02: The system should verify that there are no other clients with the same email or phone number.
    - FR_03: The system should allow the user to update the client's email, name, and phone number.
    - FR_04: The system should allow the user to inative the client's account.

Entity --> Services

    - FR_05: The system should allow to the user create services using name, duration and value.    
    - FR_06: The system should verify that there are no other services with the same name and id.
    - FR_07: The system should allow to the user update the service's atributes.
    - FR_08: The system should allow to the user inative the services.

Entity --> Appointments

    - FR_09: The system should allow the user to create appointments using Client, service, profissional, date and time
    - FR_10: Ths system should verify that there are no other appointment with the same date, time and professional. 
    - FR_11: By default, the service duration is assigned to the duration of the appointments; however, the system should allow the appointment duration to be changed if a duration is specified in the appointments.
    - FR_12: Appointments should allow the selection of more than one service; if more than one service is available, the duration must be entered in the appointment, not in the service itself.
    - FR_13: The system should allow the user to update the appointment's services, duration, date, time and profissional.
    - FR_14: The system should allow the user to inative the appointments.

Entity --> Professionals

    - FR_15: The system should allow the user to create professionals using name, e-mail and phone number.
    - FR_16: The system should verify that there are no other professionals with the same E-mail or phone number.
    - FR_17: The system should allow the user to update professional's name, e-mail and phone number.
    - FR_18: The system should allow the user to inative professionals.