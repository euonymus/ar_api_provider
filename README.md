# ar_api_provider
place your own /src/hosts/host_settings.rb file with following format

    TOKEN = '{YOUR_PRIVATE_KEY_TO_DIGITALOCEAN}'
    HOSTNAME = 'ar-api-prod'
    CHEF_ENVIRONMENT = 'production'
    PRIVATE_KEY_PATH = '~/.ssh/id_rsa'
    SSH_KEYNAME = '{YOUR_SSH_KEYNAME_ON_DIGITALOCEAN}'
