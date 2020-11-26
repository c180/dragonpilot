cd /data/ && \
rm -rf openpilot && \
git clone https://github.com/dragonpilot-community/dragonpilot.git openpilot -b testing && \
cd openpilot/scripts/ && \
./reset_update.sh
