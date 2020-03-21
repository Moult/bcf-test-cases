# multiple viewpoints without comments

This test case verifies support for only parent component listed in visualization

## Testing process

1. Load _Architectural.ifc_ from the test cases root directory
2. Import _only_parent_component_listed.bcfzip_
3. Verify the bcfzip was imported correctly:

> Verification paragrpah 1
> 1. Bcfzip file has one issue with one viewpoint
> 2. The viewpoint has curtainwall visible

> Verification paragrpah 2 

3. Export the topic you imported to _exported.bcfzip_
4. Verify that there is only one component (with IfcGuid="2_hQ1Rixj6lgHTra$L72O4") in the component section of viewpoint.bcfv

## (Optional) special notes

This is an optional section 

