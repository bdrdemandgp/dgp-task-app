# dgp-task-app

Public, **dataless** shell for the DGP Task Manager. Contains no tasks, no client names,
and no repo path — just the empty UI. On load it asks for a GitHub repo + fine-grained
token (entered once per device, stored only in your browser) and pulls your private data.
Without a token it shows nothing. All real data lives in a separate private repo.
