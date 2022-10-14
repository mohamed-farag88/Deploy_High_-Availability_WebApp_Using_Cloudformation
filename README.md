# Deploy_High_-Availability_WebApp_Using_Cloudformation
### Architecture
![Architecture](https://github.com/mohamed-farag88/Deploy_High_-Availability_WebApp_Using_Cloudformation/blob/72f20275d992bcccf0ebf4895ebaeab97fcf2cf6/Web%20APP%20Architecture.jpeg)

### To craete stack use create_stack shell script as shown:

```sh
./create_stack.sh <Stack_name> <Stack YAML File> <Stack Parameters Json File>

Example:

./create_stack.sh project2webappserver server.yaml server_parameters.json
```

### To update stack use create_stack shell script as shown:

```sh
./update_stack.sh <Stack_name> <Stack YAML File> <Stack Parameters Json File>

Example:

./update_stack.sh project2webappserver server.yaml server_parameters.json
```


### To delete stack use create_stack shell script as shown:

```sh
./delete_stack.sh <Stack_name>

Example:

./delete_stack.sh project2webappserver
```
