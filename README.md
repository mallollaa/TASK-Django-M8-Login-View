Let's secure our views!

## Steps

1. Fork and clone [this repository](https://github.com/JoinCODED/TASK-Django-M8-Login-View).
2. Create a `virtual environment`.
3. Install the packages using `pip install -r requirements/dev.lock`.
4. Create a login api, [this package](https://pypi.org/project/djangorestframework-simplejwt/) will help.
   - Create a `URL` with name `login`.
5. Create a Booking create API view:
   - It should use the same serializer as the update view.
   - The `flight` should get assigned automatically to the booking. The flight id should be retrieved from the url.
   - The `user` should get assigned automatically to the booking. The **logged in user** who is creating the booking should get assigned as the `user`.
   - Create a `URL` with name `book-flight` for this view and test it in `postman`.
6. Push your code.
