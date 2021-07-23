FROM docker/compose:debian-1.29.2

RUN apt update -y && apt install -y curl wget nano sudo

RUN curl -fsSL https://deb.nodesource.com/setup_lts.x | bash -

RUN apt update -y && apt install -y nodejs
