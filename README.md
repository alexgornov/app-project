1) Add certificates (nginx.crt, nginx.key) to roles/nginx/files/conf/ssl
2) Configure hosts file
3) run ansible playbook: 
`ansible-playbook -i hosts run.yml -kK`