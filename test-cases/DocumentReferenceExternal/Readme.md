# Document Reference External

This test case verifies support of a document reference that is external to the BCFZip file, referenced with an absolute URL.

## Testing process

1. Import _DocumentReferenceExternal.bcfzip_.
2. Verify the bcfzip was imported correctly:
> 1. Your application is aware of the absolute reference to the document outside of the BCFzip as given in the _DocumentReferences_ property in the _markup.bcf_ file.
> 2. The .xsd file attachment can be retrieved (public download from buildingsmart-tech.org).

3. Export the topic you imported to _exported.bcfzip_.
4. Verify that no information was lost during the export