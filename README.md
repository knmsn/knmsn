```javascript
async function user(req, res) {
  try {
    const user = {
      name: "Gustavo O.R",
      age: 23,
      stacks: [
        {
          NodeJS: ["ReactJS", "ReactNative", "NestJS", "Express"],
          Java: ["Spring", "JSP"],
          Kotlin:  ["Spring"],
          Python:  ["Flask", "Django", "Selenium"],
        }
      ],
      Databases: ["DB2", "SQL Server", "Amazon RDS", "Amazon Aurora", "PostgreSQL", "MongoDB", "OracleDB"],
      Cloud: ["AWS Amazon", "Microsoft Azure"],
    };

    return res.status(201).json(user);
  } catch (error) {
    return res.status(500).json({ error: "Internal Error" });
  }
}
app.get('/api/user', user);
```

<div align="left">
        <div align="center">
          <div>
            <img src="https://github-readme-stats.vercel.app/api?username=knmsn&theme=vue-dark&bg_color=0B0F12&hide_border=true&show_icons=true&include_all_commits=true&count_private=true" />
          </div>
          <div>
            <img src="http://github-readme-streak-stats.herokuapp.com?user=knmsn&theme=vue-dark&background=0B0F12&hide_border=true&date_format=M%20j%5B%2C%20Y%5D&currStreakNum=DDDDDD&sideNums=DDDDDD&include_all_commits=true&count_private=true" />
          </div>
          <div>
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=knmsn&theme=vue-dark&bg_color=0B0F12&hide_border=true&show_icons=true&include_all_commits=true&count_private=true" />
          </div>
        </div>
  </div>

<div align="center">
[![trophy](https://github-profile-trophy.vercel.app/?username=knmsn&row=2&column=3)](https://github.com/knmsn)
</div>

