# Debian
<pre><code>apt update -y && apt upgrade -y && apt dist-upgrade -y && reboot</code></pre>
# Ubuntu
<pre><code>apt update && apt upgrade -y && update-grub && sleep 2 && reboot</pre></code>
# Install
<pre><code>sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl && wget https://raw.githubusercontent.com/Anggajrxxx/v1/main/setup.sh && chmod +x setup.sh && ./setup.sh</code></pre>
