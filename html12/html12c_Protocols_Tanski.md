**Before you start:** rename this file to `html12c_Protocols_lastname.md`, using your own last name. Watch videos 7–11 and use **Part 3** of `html12_ColorsSeoProtocols_StudyGuide.md` (in this folder) to answer. Put the file in an `html12` folder in your `htmlCssJavaScript` repo. Commit and push when you're done.

**Name:**
Grant Tanski
---

# Task 12c — Internet Protocols

Type your answers on the blank line under each **Answer:**, or fill in the tables. Explain in your own words where a question asks why.

## 1. Which protocol?

**a.** For each situation, write the protocol that does the job: **HTTP, HTTPS, FTP, SFTP, DNS, TCP, or IP**.

| Situation | Protocol |
|---|---|
| You type `example.com` and your computer needs its IP address | DNS|
| You upload your website's files to a web host | FTP|
| You log in to your bank's website | HTTPS|
| A server sends a plain web page to your browser | HTTP|
| Packet 7 of a file never arrived, so it gets sent again | TCP|
| Each packet needs an address so it reaches the right computer | IP|
| You upload files to a server and want the transfer encrypted | SFTP|

**b.** In your own words, what is a protocol? Give an example from everyday life of two people following the same "rules" so they understand each other.

**Answer:**

A protocol is a group of rules that computers collectively follow to communicate with one another. It is basically like having two people speak English in order to understand one another.

## 2. IP addresses and DNS

**c.** Which of these are valid IPv4 addresses? Write **Valid** or **Not valid**, and give the reason for any that are not.

| Address | Valid? | Reason |
|---|---|---|
| `192.168.0.1` | Valid | 4 sets of numbers are between 0-255 each|
| `10.0.300.5` | Not valid | the numbers in each section have to be less that 255|
| `172.16.4` | Not Valid | Only three numbers, not four|
| `8.8.8.8` | Valid | 4 sets of numbers are between 0-255 each|

**d.** DNS is called the internet's "phone book." Explain why that comparison makes sense.

**Answer:**

The DNS is considered the internet's "phone book" as it translates each URL into is IP address, exactly how a phone book translates a landline into a phone number.

## 3. Packets

**e.** A photo is sent across the internet. It is split into 20 packets, and they take different paths. Packet 12 arrives last and packet 5 never arrives at all. Explain what happens, and which protocol handles it.

**Answer:**

When the packets arrive, the TCP attempts to put the packets back in order, and if some are missing, it asks for any missing ones to be sent again.

## 4. HTTP and HTTPS

**f.** Write the status code for each situation.

| Situation | Status code |
|---|---|
| The page loaded fine | 200 |
| You typed a page name that does not exist | 404|
| Something broke on the server | 500|

**g.** A website has a login form but uses `http://` instead of `https://`. What is the risk? What would the browser show?

**Answer:**

The risk of using a http is that the data is sent as unencrypted, which means that hackers will have an easier time getting into the conect and extracting private info. If it is in https mode, there will be a lock at the top of the website browser that signals that it is encrypted.

**h.** What do SSL and TLS have to do with HTTPS? Which one is newer?

**Answer:**

SSL and TLS encrypt the data between the connection. SSL is older, TLS is newer.

## 5. FTP

**i.** What is FTP used for in web design? Why is SFTP a better choice than plain FTP?

**Answer:**

FTP is used in web design when moving files towards a site hosting server. SFTP is a better choice that FTP as it is encrypted, making it more secure.


## 6. The parts of a URL

**j.** Break each URL into its parts.

`https://www.medinapets.com/dogs/grooming.html`

| Part | Answer |
|---|---|
| Protocol | https:// |
| Subdomain | www |
| Domain name | medinapets |
| Top-level domain (TLD) | .com |
| Path | /dogs/ |
| File name | grooming.html |

`http://library.example.edu/books/index.html`

| Part | Answer |
|---|---|
| Protocol | http:// |
| Subdomain | library |
| Domain name | example |
| Top-level domain (TLD) | .edu |
| Path | /books/ |
| File name | index.html |

**k.** Is the second URL secure? How can you tell?

**Answer:**

The second URL is not secure, as it uses the http protocol, the unencrypted version of the https protocol.

## 7. Putting it together

**l.** These steps happen when you type a URL and press Enter, but they are out of order. Number them 1–5.

| Order | Step |
|---|---|
| 5 | The browser puts the packets back together and draws the page |
| 1 | DNS finds the server's IP address |
| 3 | The browser sends an HTTPS request for the page |
| 2 | TCP/IP opens a connection to the server |
| 4 | The server sends back the HTML, CSS, and images in packets |

**m.** FTP is not one of those steps. When does FTP get used instead?

**Answer:**

It is used to put files on the server before a person tries to visit the website.

## Closing 12c — Vocabulary

| Term | Your definition |
|---|---|
| Protocol | The rules computers tend to follow in order to communicate with one another.|
| IP address | The number (or string of numbers) that defines a device on a network.|
| DNS | The Domain Name System turns the domain name in the URL into an IP address.|
| Packet | A limited piece of data, often taken from some sort of media file, that is sent across a network.|
| HTTPS | The encrypted protocol for sending web pages.|
| URL | The page's full address is its Uniform Resource Locator.|
