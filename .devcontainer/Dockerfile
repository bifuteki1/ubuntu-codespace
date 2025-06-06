# GUI環境付きのUbuntuイメージを構築
FROM dorowu/ubuntu-desktop-lxde-vnc

# パスワード: vncpassword に設定
ENV PASSWORD=vncpassword

# 任意でパッケージ追加
RUN apt-get update && apt-get install -y \
    git curl vim

EXPOSE 6080
