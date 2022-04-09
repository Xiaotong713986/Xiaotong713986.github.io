---
PersonName: "{{ with slicestr .Name 4 }}{{replace . "-" " "  | strings.TrimLeft " " | title }}{{end}}"
EnrollDate: {{ slicestr .Name 0 4 }}
Description: ""
ResearchDir: "Deep Learning"
PersonAvatar: "/person/{{ with slicestr .Name 4 }}{{replace . "-" ""  | strings.TrimLeft " " | title }}{{end}}.jpg"
StudentType: "master"
---