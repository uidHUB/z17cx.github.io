## Hi there :wave:

System administrator and web developer.

I'm writing articles on system administration and development of various systems, applications and servers.

#### :construction_worker_man: I'm currently working on...
{{ range recentContributions 5 }}
- [{{ .Repo.Name }}]({{ .Repo.URL }}) ({{ humanize .OccurredAt }}){{ with .Repo.Description }}  
  {{ . }}{{ end }}
{{- end}}

#### :telescope: Recent releases
{{ range recentReleases 5 }}
- [{{ .Name }}]({{ .URL }}) ([{{ .LastRelease.TagName }}]({{ .LastRelease.URL }}), {{ humanize .LastRelease.PublishedAt }}){{ with .Description }}  
  {{ . }}{{ end }}
{{- end}}

#### :hammer: Recent pull requests
{{ range recentPullRequests 5 }}
- [{{ .Title }}]({{ .URL }}) ({{ humanize .CreatedAt }}) `{{ .State }}`  
  &#8627; [{{ .Repo.Name }}]({{ .Repo.URL }})
{{- end}}

#### :star: Recent stars
{{ range recentStars 5 }}
- [{{ .Repo.Name }}]({{ .Repo.URL }}) ({{ humanize .StarredAt }}){{ with .Repo.Description }}  
  {{ . }}{{ end }}
{{- end }}

#### :busts_in_silhouette: Recent followers
{{ range followers 5 }}
- [{{ with .Name }}{{ . }}{{ else }}{{ .Login }}{{ end }}]({{ .URL }})
{{- end }}

## Blog
{{ range rss "https://lib.onl/ru/posts/index.xml" 10 }}
- [{{ .Title }}]({{ .URL }}) ({{ humanize .PublishedAt }})
{{- end}}

## Contacts

- :earth_africa: [**WebSite**](https://kitsune.solar/) / [mail@kitsune.solar](mailto:mail@kitsune.solar)
- :hammer_and_wrench: [GitHub](https://github.com/KitsuneSolar) / [GitLab](https://gitlab.com/KitsuneSolar)
- :camera: [Instagram](https://instagram.com/KitsuneSolar)
- :briefcase: [LinkedIn](https://linkedin.com/in/KitsuneSolar)
- :movie_camera: [Twitch](https://twitch.tv/KitsuneSolar)
- :bird: [Twitter](https://twitter.com/KitsuneSolar)
- :speech_balloon: [Vk](https://vk.com/KitsuneSolar)
- :tv: [YouTube](https://youtube.com/KitsuneSolar)

<img src="https://raw.githubusercontent.com/KitsuneSolar/KitsuneSolar/main/img.01.min.svg" width="100%" alt="OctoCat" />

## Projects

<img align="right" src="https://raw.githubusercontent.com/KitsuneSolar/KitsuneSolar/main/img.octocat.gif" width="20%" alt="OctoCat" />

- [CMF Store](https://github.com/cmfstore)  
  Add-ons, plugins, modules and themes for CMS/CMF.
- [GHA Store](https://github.com/ghastore)  
  GitHub Actions store.
- [Shell Store](https://github.com/shellstore)  
  Modules for Linux Bash (ZSH) and MS PowerShell.
- [UNIX Store](https://github.com/unixstore)  
  Apps and packages for Linux and *BSD.
- [Universal AIK](https://github.com/uaik)  
  (UNIX / Linux / Windows) automated installation kit.

## Statistic

<img align="left" src="https://raw.githubusercontent.com/KitsuneSolar/KitsuneSolar/main/img.02.min.svg" width="24%" alt="OctoCat" />

<img align="right" src="https://github-readme-stats.vercel.app/api?username=KitsuneSolar&show_icons=true" width="64%" alt="Statistic" />
