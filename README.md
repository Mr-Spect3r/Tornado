# Tornado

Powerful botnet with many options

<img src="https://private-user-images.githubusercontent.com/191456490/418297482-2703dbf2-babf-487b-9b10-5e48f2895f7f.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDA4NTM2NjUsIm5iZiI6MTc0MDg1MzM2NSwicGF0aCI6Ii8xOTE0NTY0OTAvNDE4Mjk3NDgyLTI3MDNkYmYyLWJhYmYtNDg3Yi05YjEwLTVlNDhmMjg5NWY3Zi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwMzAxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDMwMVQxODIyNDVaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1hMGU4MmI3MjlhMWUyN2QyZWE5N2MwZDVjN2E3MTFkYWFkNmZiMTJhODMzM2RmZTdmOGFjYjUyM2FkY2VlNGFhJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.hd5S26iX73Z8ecDT4rZuM9AbaPF37ppvcSJUKsdYG8U">

Options:

```
--query 1/2/3 - query string with rand ex 1 - ?cf__chl_tk 2 - ?fwfwfwfw 3 - q?=fwfwwffw
--delay <1-1000> - delay between requests 1-100 ms (optimal) default 1 ms
--cookie "f=f" - for custom cookie
--bfm true/null - bot fight mode change to true if you need dont use if no need
--referer https://target.com / rand - use custom referer if you need and rand - if you need generate domains ex: fwfwwfwfw.net
--postdata "user=f&pass=%RAND%" - if you need data to post req method format "user=f&pass=f"
--randrate - randomizer rate 1 to 90 good bypass to rate
--full - this new func for attack only big backend ex amazon akamai and other... support cf
--http 1/2/mix - new func choose to type http 1/2/mix (mix 1 & 2)
--debug - show your status code (maybe low rps to use more resource)
--header "f:f" or "f:f#f1:f1" - if you need this use custom headers split each header with #
```

# Prerequisites

```
npm install hpack
```

# Run

```
node run Tornado.js
```
