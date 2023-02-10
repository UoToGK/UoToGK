### Hi here 👋

<!--
**UoToGK/UoToGK** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!-- ![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=UoToGK&show_icons=true&theme=radical)      [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=UoToGK&layout=compact)](https://github.com/anuraghazra/github-readme-stats) -->
<!-- ![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=UoToGK&hide=contribs,prs) -->
<!-- [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=UoToGK)](https://github.com/anuraghazra/github-readme-stats) -->

```python
import base64, zlib

zstring = (
    "eNolkd1ygjAQRu/z1KgVFS2IBVFRq+JY/EFRR42o5WGa3SRXfYUuZYaLkP3O2U3CsOli7azDWBsm"
    "XirQdQW3GLixyrYqt/Exx2CGfop8jaM+BgHw8e+zI+4DOTF0ZONlg4MqtnZMcLuMwi3WJ04mWK7l"
    "OlN5Bb6HBfN84uAgXg6MY1W/C55A6ogsE9zQozrxHnR3VCO4LOtKoPL7j1GBeUcPb2Cb4JxoX47e"
    "VN3TPGKYLDG4khv2NUwigqUXgxUWHWq8UDw/oJFh6kG4YGC36Uf7OX3kEJkLvU45s5zMcbEiQC22"
    "qscpRgEIp5CbMG4ycFxdv1AfZZLYKBqO4/J4xGC6xPREmF45TFcjkYWkge5U8DZpCmzk6+iT1thv"
    "4MCmsaH5oAxaIfZ6xdil6LJHzhkGX4L3pd8hQC5s2WqIl60OiVzn6moVYx+rxIjXTBln6XtUgvec"
    "qcPx/zbfsZ/gw6UHwNsRuQXLDenZH+1eWdk="
)
zstring = base64.b64decode(zstring)
zstring = zlib.decompress(zstring, 15)
string = zstring.decode("utf-8")
print(string)
```
