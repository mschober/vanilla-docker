# Kata 1
> Timebox the activity to ~15minutes. If you don't get all the way through it call it a day and redo the kata tomorrow. Once you can complete all the excercise in ~5m you have mastered it and can return to refresh later down the road.
 
## Making a vanilla docker container
### Setup network
 - create a new network called kata
 - list the docker networks
### Create the container
 - use ubuntu image on docker.io
 - create a process that prints hello and sleeps in between
 - run it as a daemon
 - name it 'hello_world'
 - print the logs from the container
 - register the container to the kata network
 - verify the container is in the correct network
### Cleanup the container
 - stop the container
 - verify that the hello_world container is in the images list
 - remove the container
 - verify the container has been removed

## Future steps
 - create another docker container
 - name it something different
 - verify it comes up in the default network
 - login to the second container and verify it cannot talk to hello_world container
 - connect the second container to the hello_world network
 - verify they can ping eachother
