FROM cimg/android:2024.10.1-node

USER root

RUN npm i -g pnpm@8.15.4

COPY ./entrypoint.sh /home/node/entrypoint.sh
RUN chmod +x /home/node/entrypoint.sh

CMD [ "/home/node/entrypoint.sh" ]
