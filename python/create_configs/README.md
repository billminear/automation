
## create_configs.py

This is a simple example of converting YAML into a Cisco  
configuration using Python and Jinja2 templates.

```sh
# Modify .yaml and .j2 files as needed.
vim devices.yaml
vim l2_switch.j2
vim router.j2

# When ready, execute create_configs.py.
python3 create_configs.py

# Configuration files are stored in a "configs" directory
# located in the same directory that create_configs.py was
# executed in.
````
