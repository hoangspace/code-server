FROM codercom/code-server:1.621
ARG USER_ID
ARG GROUP_ID
USER root
RUN usermod -u ${USER_ID} coder && groupmod -g ${GROUP_ID} coder && \
    chown -R coder:coder /home/coder
USER coder
