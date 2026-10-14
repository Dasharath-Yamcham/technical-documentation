## Prod Deployment Microservices Mr Yoda Feb-09-2026

## Micro Services Implementation

    api-admin-service
    api-createorder-service
    api-test-service
    api-user-service
    api-db-service
    api-doctor-service
    api-notification-service

## Membership Discount – Cap Limit (Requirement)

Membership discount is capped at a maximum of ₹1000.
Any calculated discount exceeding ₹1000 will be limited to ₹1000.

## COD Order & Delivery Charges Logic (Requirement)

Delivery charges are waived for orders with a total order value of ₹999 or above.
If a member order is cancelled and the remaining order value falls below ₹1000, home sample collection charges will be applied correctly.

## Admin Panel Updates (Requirement)

Payment link generation enabled for Raw Orders.
Admin Panel frontend enhancements and stability improvements implemented.