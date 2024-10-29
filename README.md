<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   
</head>
<body>

<h1>Hotel Management System <b>(Oracle Database)</b></h1>

<h3>Project Summary</h3>
<p>This project is a Hotel Management System built with Oracle Database. It is designed to streamline and automate core hotel operations such as guest management, reservations, room management, billing, employee management, and service tracking.</p>

<h3>System Overview</h3>

<ul>
    <li>
        <b>Guest</b><br>
        Stores guest details with <code>guest_id</code> as the primary key and an associated sequence <code>guest_id_seq</code>.
    </li>
    <li>
        <b>Reservation</b><br>
        Manages reservation records with foreign keys linking to both the <code>Guest</code> and <code>Room</code> tables, enabling efficient reservation tracking.
    </li>
    <li>
        <b>Room</b><br>
        Details information about each room, linking to <code>Room_Type</code> and <code>Room_Status</code> tables for managing availability and categorization by room type.
    </li>
    <li>
        <b>Check-In and Check-Out</b><br>
        Tracks reservation check-in and check-out times to ensure smooth guest handling and availability management.
    </li>
    <li>
        <b>Billing</b><br>
        Associates billing information with reservations, enabling accurate and streamlined payment and invoicing.
    </li>
    <li>
        <b>Employee, Department, Position</b><br>
        Stores data on employees, with references to their respective <code>Department</code>, <code>Position</code>, and shift details.
    </li>
    <li>
        <b>Service and Service_Type</b><br>
        Manages additional services available to guests, enhancing the overall guest experience with amenities.
    </li>
    <li>
        <b>Menu and Orders</b><br>
        Tracks food and service orders made by guests, supporting both restaurant and room service functionalities.
    </li>
    <li>
        <b>Feedback</b><br>
        Allows guests to submit feedback on their stay, linked directly to the <code>Guest</code> table for reference and follow-up.
    </li>
</ul>

<p>This system layout provides a robust foundation for managing hotel operations efficiently, maintaining data integrity, and offering a seamless experience for both staff and guests.</p>

</body>
</html>
