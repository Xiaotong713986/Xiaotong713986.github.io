---
PersonName: "{{ with slicestr .Name 10 }}{{replace . "-" " "  | strings.TrimLeft " " | title }}{{end}}"
EnrollDate: {{ slicestr .Name 0 10 }}
Description: ""
ResearchDir: "Deep Learning"
PersonAvatar: "/person/{{ with slicestr .Name 10 }}{{replace . "-" ""  | strings.TrimLeft " " | title }}{{end}}.jpg"
StudentType: "master"
---