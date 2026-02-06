# Abaqus vumat example

Run the attached `test.inp` job with the following command:

```bash
abaqus job=test user=vumat.f interactive
```
where the `vumat.f` sub-routine implements linear elasticity as an example.
The `test.inp` file contains a single hexahedral element.

This was tested with Abaqus 2023.