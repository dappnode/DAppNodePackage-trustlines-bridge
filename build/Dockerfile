#FROM trustlines/bridge:release20955 
FROM trustlines/bridge@sha256:c1f6723fbac027b3106d602b819dcab514da9720de526b75104f4bc6ec00e00e

COPY bridge-config.toml /bridge-config.toml

ENTRYPOINT [ "/opt/bridge/bin/tlbc-bridge", "-c", "/bridge-config.toml" ]