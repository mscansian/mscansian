# About me

I've been writing Go and Python for quite a while, mostly finance things: banking, payments, accounting, that kind of stuff. Comes with the usual amount of Postgres and AWS, as these things tend to.

Feel free to reach out to me in Portuguese, English, or Italian. German works too, but beware, it might be rusty.

[LinkedIn](https://linkedin.com/in/cansian)

# A few side projects
Stay at this long enough and you start spotting the things nobody quite got around to fixing: Tools that almost do what you want, friction everyone's learned to tolerate, problems nobody noticed. These are mostly me fixing one of those for myself. Sometimes it turns out useful for other people too. Not always new ideas, most of these have been solved already, just not the way I wanted.

The other thing I keep coming back to is teaching. Explaining something is the best way I know to check whether I actually understood it, and if someone else picks it up along the way, even better. Some of the output lives below; some never made it anywhere public.

## qq — the LLM as a Unix tool
A Go-based LLM tool you can pipe into, script with, and branch on. Treats the model as a Unix tool — text in, text out, exit `0`/`1` for yes/no so it composes with `&&`, `||`, and the rest of the shell.

Built it because the obvious LLM tools (Claude Code, ChatGPT) are chat-shaped and heavy; I wanted one that lives in scripts.

[mscansian/qq](https://github.com/mscansian/qq)

## django-sql-debug
A Django development tool that prints executed ORM queries (with `EXPLAIN ANALYSE`) to the console. Works at any scope: a single query, a single test, or a whole application.

Built it because Django Debug Toolbar only renders on HTML pages and stops at the raw query — I was tired of copying queries into psql to run `EXPLAIN ANALYZE` by hand. Haven't touched it in years; keeps working through Django upgrades on its own.

[mscansian/django-sql-debug](https://github.com/mscansian/django-sql-debug)
`pip install django-sql-debug`

## m3u8-hls-downloader
A small command-line tool for downloading HLS (`m3u8`) video streams via `ffmpeg`. Supports preview-length downloads and H.264 reencoding for compatibility.

[mscansian/m3u8-hls-downloader](https://github.com/mscansian/m3u8-hls-downloader)

## Avalia Fit
A mobile-first web app for personal trainers to record physical assessments and share a results page with each client. Built it for myself (as the athlete), I wanted assessments that were quick to log at the gym and a results page I'd actually want to open later. Django + Vue.

[avaliafit.riesen.cloud](https://avaliafit.riesen.cloud)

## DrPexe YouTube channel
A Portuguese-language YouTube channel explaining computing concepts to curious non-technical folks. The aim sits between university-style depth (jargon-heavy) and broad-audience explainers (accessible but shallow) — harder to write than either, which is partly why episodes take so long. Started in 2016, just shy of 2k subscribers. Dormant for a while now, never quite found the time to keep it up. People still ask when it comes back. Maybe one day.

[youtube.com/@DrPexe1](https://www.youtube.com/@DrPexe1)

## blog.drpexe.com
A blog I kept in the early 2010s about AI for games. Started it to work through Ian Millington's *Artificial Intelligence for Games*, which I'd picked up from the uni library — explaining a topic is the test of whether you actually got it. Only covered things that weren't already well-explained on the web. Long gone; one post stuck around on Medium because people kept linking to it.

[A* with Navigation Meshes](https://medium.com/@mscansian/a-with-navigation-meshes-246fd9e72424)
