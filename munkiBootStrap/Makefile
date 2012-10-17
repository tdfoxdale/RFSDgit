#	2012-10-16
#
#	Tim Fox <tfox@rfschools.com> 2011
#	Mac OS X Systems Administrator
#
#
#	Luggage makefile for "dropping" in munki bootstrap file

include /usr/local/share/luggage/luggage.make

TITLE=Bootstrap_munki
REVERSE_DOMAIN=com.rfschools
PAYLOAD=pack-bootstrapMunki-payload
PACKAGE_VERSION=1.0
USERSHARE="/Users/Shared"

pack-bootstrapMunki-payload:
	@sudo mkdir -p ${WORK_D}${USERSHARE}
	@sudo ${CP} ./.com.googlecode.munki.checkandinstallatstartup ${WORK_D}${USERSHARE}.com.googlecode.munki.checkandinstallatstartup
