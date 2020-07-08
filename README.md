## Augsburg Babel-Development Version

### v0.0.1_babel-buggy
  git clone -b christf_next https://github.com/christf/gluon gluon-auto
 
  cd gluon-auto
  
  git clone https://github.com/freifunk-augsburg/site-ffa.git site
  
  make update
  
  ./site/build.sh -d -v -j2 (-h for help)


Dump

/site/build.sh -d -v -j2
Set GCC_J to 2
  Set GLUON_BRANCH to "experimental"!
  ~/gluon-auto/site ~/gluon-auto
  site.mk:40: /specific_site.mk: No such file or directory
  make: *** No rule to make target '/specific_site.mk'.  Stop.
  GLUON_CHECKOUT:
  GLUON_BRANCH: experimental
  GLUON_RELEASE:
  ...
  ~/gluon-auto ~/gluon-auto/site ~/gluon-auto
  Cleanup old image directory? (y/N) y
  grep: include/toplevel.mk: No such file or directory
  Preparing gluon build ...
  Making dirclean ...
  make[1]: Entering directory '/home/christian/gluon-auto/openwrt'
  make[2]: Entering directory '/home/christian/gluon-auto/openwrt'
  make[2]: Leaving directory '/home/christian/gluon-auto/openwrt'
  WARNING: Makefile 'package/feeds/packages/acme/Makefile' has a dependency on 'luci-base', which does not exist
  WARNING: Makefile 'package/feeds/packages/acme/Makefile' has a dependency on 'luci-compat', which does not exist
  WARNING: Makefile 'package/feeds/routing/bird1-ipv4-openwrt/Makefile' has a dependency on 'luci-base', which does not exist
  WARNING: Makefile 'package/feeds/routing/bird1-ipv6-openwrt/Makefile' has a dependency on 'luci-base', which does not exist
  WARNING: Makefile 'package/feeds/packages/dynapoint/Makefile' has a dependency on 'luci-lib-nixio', which does not exist
  WARNING: Makefile 'package/feeds/routing/luci-app-bmx6/Makefile' has a dependency on 'luci-lib-json', which does not exist
  WARNING: Makefile 'package/feeds/routing/luci-app-bmx6/Makefile' has a dependency on 'luci-base', which does not exist
  WARNING: Makefile 'package/feeds/routing/luci-app-bmx6/Makefile' has a dependency on 'luci-lib-httpclient', which does not exist
  WARNING: Makefile 'package/feeds/routing/luci-app-bmx7/Makefile' has a dependency on 'luci-lib-json', which does not exist
  WARNING: Makefile 'package/feeds/routing/luci-app-bmx7/Makefile' has a dependency on 'luci-mod-admin-full', which does not exist
  WARNING: Makefile 'package/feeds/routing/luci-app-cjdns/Makefile' has a dependency on 'luci-base', which does not exist
  WARNING: Makefile 'package/feeds/packages/prometheus-node-exporter-lua/Makefile' has a dependency on 'luci-lib-nixio', which does not exist
  WARNING: Makefile 'package/feeds/packages/sqm-scripts/Makefile' has a dependency on 'luci-base', which does not exist
  WARNING: Makefile 'package/feeds/packages/sqm-scripts/Makefile' has a dependency on 'luci-compat', which does not exist
   make[2] dirclean
  make[1]: Leaving directory '/home/christian/gluon-auto/openwrt'
  Branch 'master' set up to track remote branch 'master' from 'origin'.
  Switched to a new branch 'master'
  Already up to date.
  Your branch is up to date with 'origin/master'.
  make[1]: Entering directory '/home/christian/gluon-auto/openwrt'
  Checking 'working-make'... ok.
  Checking 'case-sensitive-fs'... ok.
  Checking 'proper-umask'... ok.
  Checking 'gcc'... ok.
  Checking 'working-gcc'... ok.
  Checking 'g++'... ok.
  Checking 'working-g++'... ok.
  Checking 'ncurses'... ok.
  Checking 'perl-thread-queue'... ok.
  Checking 'tar'... ok.
  Checking 'find'... ok.
  Checking 'bash'... ok.
  Checking 'patch'... ok.
  Checking 'diff'... ok.
  Checking 'cp'... ok.
  Checking 'seq'... ok.
  Checking 'awk'... ok.
  Checking 'grep'... ok.
  Checking 'getopt'... ok.
  Checking 'stat'... ok.
  Checking 'unzip'... ok.
  Checking 'bzip2'... ok.
  Checking 'wget'... ok.
  Checking 'perl'... ok.
  Checking 'python3-cleanup'... ok.
  Checking 'python'... ok.
  Checking 'git'... ok.
  Checking 'file'... ok.
  Checking 'ldconfig-stub'... ok.
  make[2]: Entering directory '/home/christian/gluon-auto/openwrt'
  make[2]: Leaving directory '/home/christian/gluon-auto/openwrt'
  Collecting package info: done
  Collecting target info: done
  WARNING: Makefile 'package/feeds/packages/acme/Makefile' has a dependency on 'luci-base', which does not exist
  WARNING: Makefile 'package/feeds/packages/acme/Makefile' has a dependency on 'luci-compat', which does not exist
  WARNING: Makefile 'package/feeds/routing/bird1-ipv4-openwrt/Makefile' has a dependency on 'luci-base', which does not exist
  WARNING: Makefile 'package/feeds/routing/bird1-ipv6-openwrt/Makefile' has a dependency on 'luci-base', which does not exist
  WARNING: Makefile 'package/feeds/sargon/ddhcpd/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/sargon/ddhcpd-batman-adv/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/packages/dynapoint/Makefile' has a dependency on 'luci-lib-nixio', which does not exist
  WARNING: Makefile 'package/feeds/ffffmpackages/ffffm-ath9k-broken-wifi-workaround/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/ffffmpackages/ffffm-autoupdater-use-site-conf-branch/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/ffffmpackages/ffffm-banner/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/ffffmpackages/ffffm-banner_legacy/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/ffffmpackages/ffffm-button-bind/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/ffffmpackages/ffffm-helper-tools/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/ffffmpackages/ffffm-keep-radio-channel/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/ffffmpackages/ffffm-restart-respondd/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-alfred/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-authorized-keys/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-autoupdater/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-client-bridge/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-config-mode-autoupdater/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-config-mode-contact-info/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-config-mode-core/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-config-mode-domain-select/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-config-mode-geo-location/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-config-mode-hostname/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-config-mode-mesh-vpn/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-config-mode-theme/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-core/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-ebtables/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-ebtables-filter-multicast/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-ebtables-filter-ra-dhcp/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-ebtables-limit-arp/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-ebtables-source-filter/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-l3roamd/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-lock-password/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-mesh-batman-adv/Makefile' has a dependency on 'kmod-batman-adv-legacy', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-mesh-batman-adv/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-mesh-vpn-core/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-mesh-vpn-fastd/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-mesh-vpn-tunneldigger/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-neighbour-info/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-node-info/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-radv-filterd/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-radvd/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-respondd/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-setup-mode/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-site/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-status-page/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-status-page-mesh-batman-adv/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-wan-dnsmasq/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-web/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-web-admin/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-web-autoupdater/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-web-logging/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-web-mesh-vpn-fastd/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-web-model/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-web-network/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-web-node-role/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-web-osm/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-web-private-wifi/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/gluon_base/gluon-web-wifi-config/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/routing/luci-app-bmx6/Makefile' has a dependency on 'luci-lib-json', which does not exist
  WARNING: Makefile 'package/feeds/routing/luci-app-bmx6/Makefile' has a dependency on 'luci-base', which does not exist
  WARNING: Makefile 'package/feeds/routing/luci-app-bmx6/Makefile' has a dependency on 'luci-lib-httpclient', which does not exist
  WARNING: Makefile 'package/feeds/routing/luci-app-bmx7/Makefile' has a dependency on 'luci-lib-json', which does not exist
  WARNING: Makefile 'package/feeds/routing/luci-app-bmx7/Makefile' has a dependency on 'luci-mod-admin-full', which does not exist
  WARNING: Makefile 'package/feeds/routing/luci-app-cjdns/Makefile' has a dependency on 'luci-base', which does not exist
  WARNING: Makefile 'package/feeds/packages/prometheus-node-exporter-lua/Makefile' has a dependency on 'luci-lib-nixio', which does not exist
  WARNING: Makefile 'package/feeds/sargon/roamguide/Makefile' has a build dependency on 'luci-base/host', which does not exist
  WARNING: Makefile 'package/feeds/packages/sqm-scripts/Makefile' has a dependency on 'luci-base', which does not exist
  WARNING: Makefile 'package/feeds/packages/sqm-scripts/Makefile' has a dependency on 'luci-compat', which does not exist
  touch .config
  [ -L .config ] && export KCONFIG_OVERWRITECONFIG=1; \
  	scripts/config/conf --defconfig=.config Config.in
  #
  # configuration written to .config
  #
  make[1]: Leaving directory '/home/christian/gluon-auto/openwrt'
  Configuration failed:
   * unable to enable package 'gluon-mesh-babel'
   * unable to enable package 'gluon-iptables-clamp-mss-to-pmtu'
   * unable to enable package 'prefixd'
   * unable to enable package 'gluon-web-prefixd'
   * unable to enable package 'gluon-464xlat-clat'
   * unable to enable package 'gluon-ddhcpd'
   * unable to enable package 'gluon-mesh-vpn-wireguard'
  Makefile:124: recipe for target 'config' failed
  make: *** [config] Error 1





### v0.0.1_babel-work
Etwas gepatches Gluon, angereichert mit den Configs für Freifunk-Augsburg et viola nach ca. 8 Stunden compiletime habt Ihr im output-Ordner Firmwares liegen

  git clone -b christf_next https://github.com/christf/gluon
  
  cd gluon
  
  git clone https://github.com/freifunk-augsburg/site-ffa.git site
  
  make update
  
  make GLUON_TARGET=ar71xx-generic


#### Known Issues
Entwicklerversion. Es ist mehr kaputt als geht.
