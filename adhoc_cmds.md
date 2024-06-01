Running nginx on web nodes with an ad-hoc command.

  `ansible -i hosts -m shell -a "sudo apt update && sudo apt install -y nginx && sudo systemctl start nginx && sudo systemctl enable nginx" web`
