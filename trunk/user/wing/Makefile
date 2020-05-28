THISDIR = $(shell pwd)

all:

config_test:

clean:

romfs:
	$(ROMFSINST) $(THISDIR)/gfwlist.conf /etc_ro/gfwlist.conf
	$(ROMFSINST) -p +x $(THISDIR)/ipt2socks /usr/bin/ipt2socks
	$(ROMFSINST) -p +x $(THISDIR)/dns2tcp /usr/bin/dns2tcp
	$(ROMFSINST) -p +x $(THISDIR)/dns-forwarder /usr/bin/dns-forwarder
	$(ROMFSINST) -p +x $(THISDIR)/trojan /usr/bin/trojan
	$(ROMFSINST) -p +x $(THISDIR)/wing /usr/bin/wing
