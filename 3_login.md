Feature: Login

Definition of Done

    1. UI is satisfactory
    2. User can input data
    3. User can submit data
    4. Password hash can be compared
    5. Check user data on db
    6. Visual confirmation of login (message change OR console log)
    7. Code format checked
    8. Push and merge on GH

Steps:

    BE:
        1. User model
        2. POST route 'login'
        3. Middleware comparePassword

    FE:
        1. Add input (changehandler)
        2. Add submit (handleSubmit)
        3. Add state (username, password)
        4. Add fetch request
        5. Console.log response/data
