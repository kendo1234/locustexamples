Tutorial Source: https://medium.com/better-programming/introduction-to-locust-an-open-source-load-testing-tool-in-python-2b2e89ea1ff

Run Locust: *locust -f locustfile.py*
- Then head to http://localhost:8089/

Run without dashboard: locust -f locustfile.py --headless --host test -u 1000 -r 100

