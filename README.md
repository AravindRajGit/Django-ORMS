# Django-ORMS

Here iam going show some basic and simple ORMS based on Passenger Model Class

<img src="images/Capture.PNG" width="760" height="320">


1. Creating Objects

       Methode-1
      
       >>> passengerObj = Passenger(first_name='Aravind',last_name='Raj')
       >>> passengerObj.save()
       
       Methode-2
       
       >>>Passenger.objects.create(first_name='Aravind',last_name='Raj')


1. Select all datas or objects from Model

       >>>Passenger.objects.all()
       
2. Select a object or data based on id

       >>>Passenger.objects.get(id=...)

3. Delete all objects from model

       >>>Entry.objects.all().delete()
