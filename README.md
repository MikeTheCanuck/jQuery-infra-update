# jQuery-infra-update
Code to assist in automatically updating the hosts underlying the jQuery infrastructure

Design principles:
- we don't want to be bothered by more unnecessary email
- we want these updates to run at *least* once a day
- we're following the defaults because they make sense in our context (servers are cattle not pets, we can always rebuild if something horrible happens)