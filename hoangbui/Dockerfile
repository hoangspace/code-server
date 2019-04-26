FROM codercom/code-server:1.621
ARG USER_ID
ARG GROUP_ID

RUN usermod -u ${USER_ID} coder && usermod -g ${GROUP_ID} coder && \
    chown -R coder:coder /home/coder
