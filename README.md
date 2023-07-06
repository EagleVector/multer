# multer

Multer is a node.js middleware for handling multipart/form-data, which is primarily used for uploading files.

## Usage

Multer adds a body object and a file or files object to the request object. The body object contains the values of the text fields of the form, the file or files object contains the files uploaded via the form.

## storage

### DiskStorage

The disk storage engine gives you full control on storing files to disk.