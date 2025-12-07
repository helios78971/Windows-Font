# Step by step
sudo mkdir -p /usr/local/share/fonts/msfonts

sudo cp -r fonts/*.ttf /usr/local/share/fonts/msfonts

sudo cp -r fonts/*.ttc /usr/local/share/fonts/msfonts

sudo chown -R root: /usr/local/share/fonts/msfonts

sudo chmod 644 /usr/local/share/fonts/msfonts/*

sudo restorecon -vFr /usr/local/share/fonts/msfonts

sudo fc-cache -v
