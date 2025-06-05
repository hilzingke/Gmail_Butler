# Code Citations

## License: unknown
https://github.com/mortalis13/PythonScripts/tree/352c3623bae94b072760c34a99e425fb9c87f4e4/rss_service.py

```
= InstalledAppFlow.from_client_secrets_file('credentials.json', SCOPES)
        creds = flow.run_local_server(port=0)
        with open('token.pickle', 'wb') as token:
            pickle.dump(creds, token)
    service = build('gmail',
```


## License: unknown
https://github.com/syambasiva/AIQ_Customecodes/tree/93318e7b661a035521292e1d4e608640949f3bb5/Gmail/Thinkperfect_Gmail.py

```
('credentials.json', SCOPES)
        creds = flow.run_local_server(port=0)
        with open('token.pickle', 'wb') as token:
            pickle.dump(creds, token)
    service = build('gmail', 'v1',
```

gmail_analyzer/
├── app.py
├── requirements.txt
├── templates/
│   ├── index.html
│   ├── analysis.html
│   └── confirm_delete.html
├── static/
│   └── style.css
├── gmail_service.py
└── README.md

