FROM python:3
WORKDIR /usr/src/app

COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

# NOTE: Does not work yet, working out details w/ X11 forwarding
CMD [ "python", "-m", "pygame.examples.aliens" ]
