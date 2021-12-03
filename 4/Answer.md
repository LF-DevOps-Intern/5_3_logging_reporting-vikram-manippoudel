curl -fsSL https://artifacts.elastic.co/GPG-KEY-elasticsearch | sudo apt-key add -
OK

echo "deb https://artifacts.elastic.co/packages/7.x/apt stable main" | sudo tee -a /etc/apt/sources.list.d/elastic-7.x.list

sudo apt install logstash

Reference Picture:
    For logstash installation:
        log_stash_install_log_wget.png
    Enabling logstash:
        logstash_enable_start.png

