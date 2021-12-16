# salesforce-package-xml

Please refer to the blog post at the URL below for complete details about the files provided in this repo along with step-by-step instructions on on how to prepare the package.xml file yourself

https://www.asagarwal.com/how-to-retrieve-all-metadata-from-your-salesforce-org-using-package-xml

This repo contains

1. **package-all-metadata-v53.xml** - Use this file to retreive all metadata from your Salesforce Org. This will work if the number of components that needs to be retrieved is less than 10,000

2. **package-all-metadata-v53-1-of-2.xml** - If you have more than 10,000 components in your Salefsorce Org, use this file to retrieve the metdata components. In this file, the metadata types 'Group', 'Queue' & 'Role' has been commented

3. **package-all-metadata-v53-2-of-2.xml** - This is the 2nd part of the file above. This file only contains metadata types Group', 'Queue' & 'Role' has been commented

4. **package-profile.xml** - Use this file to retreive the profile and all the other metadata types that impact the Profile XML. Some of these metdata types do not work with wildcard asterisk character. A comment has been added to such metadata types. Replace asterisk with the API name of the components that needs to be retrieved

5. **package-object.xml** - Use this file to retreive an object and all the important metadata related to an object.
