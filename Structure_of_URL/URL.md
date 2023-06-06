# STRUCTURE OF URL

### URL - Uniform Resource Locator
   * It is a string of character that is used to identify a resource on internet such as webspage, images, videos and any other type of contents.

## The structure of a URL consists of several components, which include:
## 1. Scheme
   * It is a protocol [First Part of URL].
   * The protocol defines how the resource will be accessed. 
   * The most common protocols are `HTTP and HTTPS` which are used for accessing websites,
   * `FTP` which is used for transferring files &
   * `mailto` which is used for email addresses.

## 2. Authority 
   * This part of the URL contains the `Domain Name`and optionally, the `Port Number`.
   
### i. Domain Name
   * Its a Second Part of URL & Specifies the website or web server where the resource is located.
   * It can be FQDN (`Fully Qualified Domain Name`) or an `IP Address`.

There are different types of Doamin:

### 1. Top Level Domain (TLD)
   * These are the highest level domains in the domain name system (DNS) hierarchy. 
   * Examples of TLDs include .com, .org, .net, .gov, .edu, and .mil. 
   * TLDs are often used to indicate the purpose or type of organization that owns the domain.

### 2. Second Level Domain (SLD)
   * A second-level domain (SLD) is the part of the domain name that comes directly before the TLD. 
   * It is typically the name chosen by the website owner and is unique within the TLD.
   * Example: `university.edu`
* The top-level domain (TLD) is ".edu"
* The second-level domain (SLD) is "university"

### 3. Subdomain
   * These are additional domains that can be added to a URL to create a more specific address. 
   * For example, in the URL https://drive.google.com, `drive` is a subdomain of `google.com`.


### 4. Country code top-level domains (ccTLDs) 
   * These are TLDs that are associated with a specific country or geographic region. 
   * Examples of ccTLDs include .us (United States), .uk (United Kingdom), and .ca (Canada).

### 5. Internationalized domain names (IDNs) 
   * These are domain names that include non-ASCII characters, such as accented letters or characters from non-Latin scripts. 
   * IDNs are used to create domain names in languages other than English.

<pre>
Example:
例子.测试 (example.test) - This is an IDN in Simplified Chinese script.
пример.испытание (.test) - This is an IDN in Cyrillic script.
உதாரணம்.பரிட்சை (example.test) - This is an IDN in Tamil script.
</pre>

### 6. Private Domain
   * A private domain is a domain name that is used exclusively for internal purposes within a private network, such as a company or organization.
   * Private domains are not accessible from the public internet and are not registered with a domain registrar.

<pre>
Example of a private domain is "mycompany.local". 
This domain name is not registered with a domain registrar and is used only within the private network of the company. 
Other examples of private domains include ".local", ".intranet", and ".internal".
</pre>

### ii. Ports
  * Ports are an important component of a URL because they specify the endpoint that the client should use when accessing the server. 
  * The default port number for most protocols is usually implied and does not need to be specified explicitly in the URL. 
  * For example, the default port for HTTP is 80 and the default port for HTTPS is 443. 
  * However, in some cases a different port number may need to be specified in the URL. 

Here is how ports are specified in a URL:

1. The port number is separated from the domain name or IP address by a colon (":").
2. The port number is specified after the domain name or IP address.

* For example, the URL http://example.com:8080/index.html specifies that the client should connect to the server at example.com using port number 8080, and request the file "index.html". Similarly, the URL https://example.com:8443 specifies that the client should connect to the server at example.com using port number 8443, which is often used for secure communication.
* It is important to note that not all URLs require a port number to be specified. 
* In many cases, the default port number for the protocol being used will suffice and the port number can be omitted from the URL.

## 3. Path 
   * The path is the hierarchical structure that leads to the specific resource on the web server. `Third Part of URL`
   * It usually consists of a series of directory and file names separated by slashes 
   * `e.g., "/directory/subdirectory/filename.html"`

## 4. Query
   *  The query string is an optional part of the URL that provides additional information to the server. 
   *  It starts with a question mark (?) and consists of key-value pairs separated by ampersands (&). 
   *  For example, in the URL "example.com/search?q=keyword", the query string is "q=keyword".

## 5. Fragment
   *  The fragment identifier is another optional part of the URL that refers to a specific section within a web page. 
   *  It starts with a hash symbol (#) and is followed by the identifier 
   *  `e.g., "example.com/page.html#section1"`


======================================================================================


## Example

### `URL: https://www.example.com/directory/subdirectory/filename.html?q=keyword#section1`

### Scheme: https
* The scheme specifies the protocol to be used, which in this case is "https". It indicates that the resource should be accessed securely using the HTTP protocol.

### Authority:

`Hostname: www.example.com`
* The hostname is the domain name of the server that hosts the resource. In this case, it is "www.example.com".

### Port: (default port for https, so not specified)
* The port number is not specified in the URL, which means the default port for the "https" protocol (port 443) will be used.

`Username and Password: None`
* There is no username or password specified in the URL. If present, they would appear before the "@" symbol in the authority component.

### Path: /directory/subdirectory/filename.html
* The path component specifies the location of the resource on the server's file system. In this example, it includes a directory "directory", a subdirectory "subdirectory", and a filename "filename.html".

### Query String: ?q=keyword
* The query string component begins with a question mark "?" and contains key-value pairs separated by ampersands "&". In this case, the query string is "q=keyword", which means there is a single key "q" with the value "keyword". This is often used to pass parameters or search terms to the server.

### Fragment: #section1
* The fragment component starts with a hash symbol "#" and identifies a specific section or anchor within the resource. In this case, it is "section1".






