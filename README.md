Breakthrough is a simple time based SQLi scanner. It reads urls from stdin, tests each url's query parameters with a number of time based payloads and analyzes the response time.

Usage: cat list_urls | sheep -concurrency 200 | breakthrough -concurrency 200
