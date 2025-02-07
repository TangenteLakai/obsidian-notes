# lecture-8-html-css-javascript

## Terms

<table border="1">
	<thead>
		<tr>
			<th>Acronym</th>
			<th>Full Form</th>
			<th>Description</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>IP</td>
			<td>Internet Protocol</td>
			<td>Identifies and routes devices on a network</td>
		</tr>
		<tr>
			<td>TCP</td>
			<td>Transmission Control Protocol</td>
			<td>Ensures reliable data transmission</td>
		</tr>
		<tr>
			<td>DHCP</td>
			<td>Dynamic Host Configuration Protocol</td>
			<td>Assigns IP addresses to devices automatically</td>
		</tr>
		<tr>
			<td>HTTP</td>
			<td>HyperText Transfer Protocol</td>
			<td>Transfers web page data over the internet</td>
		</tr>
		<tr>
			<td>HTTPS</td>
			<td>HyperText Transfer Protocol Secure</td>
			<td>Secure version of HTTP using encryption</td>
		</tr>
		<tr>
			<td>HTML</td>
			<td>HyperText Markup Language</td>
			<td>Structures web page content</td>
		</tr>
		<tr>
			<td>CSS</td>
			<td>Cascading Style Sheets</td>
			<td>Styles and formats web pages</td>
		</tr>
	</tbody>
</table>

## IP Addresses

- Stands for **Internet Protocol**
- Address for a device on a network
- Versions:
	1. IpV4: ```#.#.#.#``` (Numbers ranging from 0-255, 32-bit)
	2. Ipv6: `xxxx:xxxx:xxxx:xxxx:xxxx:xxxx:xxxx:xxxx` (Hex numbers, 128-bit)

## TCP

- stands for **Transmission Control Protocol**
- Ensures reliable data transmission

## DHCP

- stands for **Dynamic Host Configuration Protocol**
- Assigns IP addresses to devices

## HTTP

- Stands **HyperText Transfer Protocol**
- Transfers web page data
- HTTP Status Codes: 

| 200 | OK                    |
| --- | --------------------- |
| 301 | Moved Permanently     |
| 304 | Not Modified          |
| 304 | Temporary Redirect    |
| 401 | Unauthorized          |
| 403 | Forbiddem             |
| 404 | Not Found             |
| 418 | I'm a Teapot          |
| 500 | Internal Server Error |
| 503 | Service Unavailable   |

> Use `curl -I http://www.example.com/`
> 
> to get status code of a website

- **HTTPS**: Secure Version of HTTP

## HTML

[HTML Summary](contents-html.md)

## CSS

[CSS Summary](contents-css.md)

## HTTP-Server

- Bash command to create a simple server to view webpages 
- Run on `localhost` which means Local Computer
- Terminal contains information like browser the user use and ip of the Server

## Client and Server

- when you change code in the developer tools you secretly modify on a local copy of the [HTML](contents-html.md) page while the code on the server is still the same
