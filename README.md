<samp>
  <br>
  <p align="center">
    Hi, I'm <b>「 Lain 」</b>, a <b>RPG</b> Discord bot!
  </p>
  <br>
  <b>features:</b>
  <ul>
    <li><b>Build PCs:</b> Collect parts and assemble your custom PC.</li>
    <li><b>Hack Battles:</b> Challenge enemies with your PC.</li>
    <li><b>Server Tools:</b> Manage roles and commands.</li>
  </ul>
  Invite me to your server and start your adventure!
  <br>
  <br>
  <b>building the bot:</b>
  <ul>
    <li>clone the repository: <code>git clone https://github.com/tarffie/lain.git cd lain</code></li>
    <li>build the Docker Image: <code>docker build -t lain-bot .</code></li>
    <li>run the docker container: <code>docker run -d --env-file .env lain-bot</code></li>
  </ul>
  <b>database generation & migration</b>
  <ul>
    <li>generate a new migration: <code>npx drizzle-kit generate</code></li>
    <li>migrate: <code>npx drizzle-kit migrate</code></li>
  </ul>
  <b>database connection</b>
  <ul>
    <li> login to your database: <code> psql -U ${POSTGRESDB_USER} -d ${POSTGRESDB_DATABASE} -h postgresdb -p ${POSTGRESDB_DOCKER_PORT} </code>
  </ul>

<b>contributing:</b>

  <ul>
    <li>Feel free to open issues or pull requests. Contributions are welcome!</li>
  </ul>
  <b>license:</b>
  <ul>
    <li>This project is licensed under the Apache License 2.0 - see the <a href="LICENSE">LICENSE</a> file for details.
    </li>
  </ul>
  <b>contact:</b>
  <ul>
    <li>For questions or support, contact us on <a href="https://discord.gg/">Discord</a>.</li>
  </ul>
</samp>
