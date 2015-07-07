This is my ~/pbuilder/hooks directory:  it gets set up from my ~/.pbuilderc file
with the following contents.

```
# ccache
#sudo mkdir -p /var/cache/pbuilder/ccache
#sudo chmod a+w /var/cache/pbuilder/ccache
#export CCACHE_DIR="/var/cache/pbuilder/ccache"
#export PATH="/usr/lib/ccache:${PATH}"
#EXTRAPACKAGES=ccache
#BINDMOUNTS="${CCACHE_DIR}"
BINDMOUNTS="/home/stephenw/debian/archive"
HOOKDIR=/home/stephenw/pbuilder/hooks
export DPKG_GENSYMBOLS_CHECK_LEVEL=4

```
