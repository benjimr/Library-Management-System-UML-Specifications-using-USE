Defines classes, attributes, operations, statemachines, associations, invariants and constraints for a Library management system using USE specification.

Model specifies different types of users (Members, Employees) and what each group can do, such as borrow, return or reserve books, as well as applying a fine to an account and paying a fine. Books and copies of books are also specified with controls ensuring no more than the avaialble amount of books are loaned, or loaned to a user who has already hit their limit.

## Class Diagram
![Class Diagram](https://i.imgur.com/PrLuv7X.png "Class Diagram")

## Sample Instatiated Object Diagram
![Object](https://i.imgur.com/BVpFE3a.png "Object Diagram")

## Sequence Diagrams
### Borrowing
![Borrow](https://i.imgur.com/38mWVvZ.png "Borrow")

### Returning
![Return](https://i.imgur.com/U1AP8Bd.png "Return")

### Reserving
![Reserve](https://i.imgur.com/jLaA6vY.png  "Reserve")

## State Machine
### Book Available
![Available](https://i.imgur.com/2FtGGLM.png "Available")

### Book Unavaiable
![Unavailable](https://i.imgur.com/lUQiuyC.png "Unavailable")

## Sampe Constraint Testing

### Copy of book already reserved. 
![Already Reserved](https://i.imgur.com/AmCV3if.png "Already Reserved")

### No reservation to remove
![No Reservation](https://i.imgur.com/Irq0vz0.png "No Reservation")

### Can't return a book you are not the borrower of.
![Not Borrower](https://i.imgur.com/E0FkHWP.png "Not Borrower")

### Can't return a book that was never borrowed.
![Not Borrowed](https://i.imgur.com/jB2Hu2y.png "Not Borrowed")

### Copy of book already borrowed.
![Copy already borrowed](https://i.imgur.com/lntbuX4.png "Copy already borrowed")

### Only one copy of each book allowed per user.
![One Copy Only](https://i.imgur.com/C7koVKm.png "One Copy Only")

### Can't borrow more than the borrow limit.
![Borrow Limit](https://i.imgur.com/qObEtW4.png "Borrow Limit")

### Can't overpay a fine.
![Overpaying Fine](https://i.imgur.com/eColeWN.png "Overpaying Fine")

### Can't apply a fine that exceeds the maximum.
![Max Fine](https://i.imgur.com/AjVXGAE.png "Max Fine")
