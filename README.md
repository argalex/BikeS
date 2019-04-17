# BikeS

BikeS is an online management system for a bycicle service shop.  With it users can create an appointment with the service shop to have their byciles repaired. 

To do so users must first lookup an available date and time for an appointment. They will then fill out a form with their name, email, phone number, a description of a problem and finally a few media files to showcase the defect. After review from an administrator(bike shop employee) the user will then recive an email with a positive or negative response.In case of a negative response the administrator will attach a mesage explaining the denial of the request, otherwise in case of a positive response in the email there will be a link attached.

By clicking on the link the user will be redirected to a unique page where he can see his request details, an answer from the admin and a few options for the parts needed to complete the repair. From here user can select the specific parts he would prefer to be used and can see an estimative pricing for the total cost. The user can then approve the response by clicking the "Accept" button, or he could reject the admin's response and cancel the appointment by clicking the "Cancel" button.

To access the additional features of the application, admins must log in using their account. Afther that they will be greeted by a navigation page wich will let them access the appointments page, the stocks and orders page, the management page or they can simply log out.

The appointments page will open up a calendar containing the requests.By clicking on an entry a page with the request details will open. From here the admin can approve or deny a request by adding a message and by clicking the corresponding button. In case of an approval the admin can also add a few parts that he might need for the repair and also an estimative pricing for the work.If the user accepts the response the total price for the repair will increase based on the parts that he has selected.If the user denies the response or cancels the appointment then the listing will dissapear from the appointments page.

The stocks and orders page will contain a table with all the parts that the admin has in stock, or parts that he has placed orders for. From here he can also place orders for parts where the stock has depleted. To do so the admin must go on the row of the desierd part, select a provider for it from a list, enter the quantity and the click on order. The  column orders for that part will then be updated.

The management page will be used to add new parts and new provider, this in term will update the table from the stocks and orders page. New options will be available for providers and new rows will be created for parts.From this page the admin can also export his inventory to CSV/JSON/PDF but also he can import from the same formats except PDF.
