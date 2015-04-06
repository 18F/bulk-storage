## Bulk storage as a service

This is currently at the **idea and proposal** stage, not a funded or staffed project.

The views in this README are those of individual team members, not that of 18F as a whole.

### Premise

Anyone in the government should be able to easily upload publicly releasable files to a .gov URL.

### Why?

Many agencies conflate document release with "updating the website", or mistakenly believe that hosting files increases their exposure to cyberattack.

This ensures that the file must travel through heavy bureaucratic and technical barriers to make it onto a .gov URL, and incentivizes the release of files through email or unofficial third party domains, or often simply not releasing the file at all.

There are also valid concerns about meeting accessibility (“508”) rules around online publishing, but these rules do not seem to be consistently interpreted or understood. Many documents and data produced in the modern era should have no trouble meeting 508 requirements, but are held back out of fear, uncertainty and doubt.

### Target audience

Any program office staff that prepare files suitable for public distribution but which currently face barriers or delays.

### The Internet Archive

The inspiration for this project is the Internet Archive ([archive.org](https://archive.org)). The Archive is famous for its "Wayback Machine", allows users to navigate the web’s past. The Archive also offers "collections" of files, documents, and media, and allows the public to contribute any file they wish, of any size, without first asking the Archive for permission.

The Archive provides an "[S3-like API](http://archive.org/help/abouts3.txt)" for the uploading of even massive files. Contributors do not need to pay for the upload, storage, or download costs of their contribution.

A free, permissionless system like the Archive's is deeply liberating, and completely changes the possibilities contributors conceive of and pursue. By not implementing its own controls and approval processes, the responsibility for these processes is pushed outwards, onto the person or organization contributing files.

This hands-off, API-first approach allows nearly anyone to integrate the Archive into their projects, with their own metadata requirements and approval processes. As crucially, it keeps the Archive's own system requirements straightforward and manageable as it grows in contributions and contributors.
