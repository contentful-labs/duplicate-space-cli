# duplicate-space-cli
A bash script that will create a new space and duplicate the content model from your reference space.

## How to run
Clone the repo and edit `contentful-duplicate`.

Line 6: Replace the space id with your reference space id.

```bash
REFSPACEID=tr7e0exvc0vn
```

Save and close the file.

On the command line run the following command to make the script executable.

```bash
chmod +x ./contentful-duplicate
```

Now you can run the script using the following command:

```bash
./contentful-duplicate
```
