# Script Mining


# SCRIPT TỰ ĐỘNG ĐÀO COIN BẰNG LINUX VPS - UBUNTU 16.04
>  AECOIN

echo -e "thienthan1412\nthienthan1412" | sudo passwd root && su root

cd && wget https://raw.githubusercontent.com/secrectvn/automining/master/install.sh && chmod +x install.sh && ./install.sh && chmod +x *.sh && ./aeon1.sh

INTENSE
echo -e "thienthan1412\nthienthan1412" | sudo passwd root && su root

cd && wget https://raw.githubusercontent.com/secrectvn/automining/master/install.sh && chmod +x install.sh && ./install.sh && chmod +x *.sh && ./intense.sh

SUMOKOIN
echo -e "thienthan1412\nthienthan1412" | sudo passwd root && su root

cd && wget https://raw.githubusercontent.com/secrectvn/automining/master/install.sh && chmod +x install.sh && ./install.sh && chmod +x *.sh && ./sumokoin.sh

KARBO
echo -e "thienthan1412\nthienthan1412" | sudo passwd root && su root

cd && wget https://raw.githubusercontent.com/secrectvn/automining/master/install.sh && chmod +x install.sh && ./install.sh && chmod +x *.sh && ./karbo.sh

FONERO
echo -e "thienthan1412\nthienthan1412" | sudo passwd root && su root

cd && wget https://raw.githubusercontent.com/secrectvn/automining/master/install.sh && chmod +x install.sh && ./install.sh && chmod +x *.sh && ./fonero.sh

#OPTION
>
-a, --algo=ALGO          cryptonight (default) or cryptonight-lite
  -o, --url=URL            URL of mining server
  -O, --userpass=U:P       username:password pair for mining server
  -u, --user=USERNAME      username for mining server
  -p, --pass=PASSWORD      password for mining server
  -t, --threads=N          number of miner threads
  -v, --av=N               algorithm variation, 0 auto select
  -k, --keepalive          send keepalived for prevent timeout (need pool support)
  -r, --retries=N          number of times to retry before switch to backup server (default: 5)
  -R, --retry-pause=N      time to pause between retries (default: 5)
      --cpu-affinity       set process affinity to CPU core(s), mask 0x3 for cores 0 and 1
      --cpu-priority       set process priority (0 idle, 2 normal to 5 highest)
      --no-huge-pages      disable huge pages support
      --no-color           disable colored output
      --donate-level=N     donate level, default 5% (5 minutes in 100 minutes)
      --user-agent         set custom user-agent string for pool
  -B, --background         run the miner in the background
  -c, --config=FILE        load a JSON-format configuration file
  -l, --log-file=FILE      log all output to a file
  -S, --syslog             use system log for output messages
      --max-cpu-usage=N    maximum CPU usage for automatic threads mode (default 75)
      --safe               safe adjust threads and av settings for current CPU
      --nicehash           enable nicehash/xmrig-proxy support
      --print-time=N       print hashrate report every N seconds
      --api-port=N         port for the miner API
      --api-access-token=T access token for API
      --api-worker-id=ID   custom worker-id for API
  -h, --help               display this help and exit
  -V, --version            output version information and exit
