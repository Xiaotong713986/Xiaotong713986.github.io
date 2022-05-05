---
PersonName: "{{ with slicestr .Name 4 }}{{replace . "-" " "  | strings.TrimLeft " " | title }}{{end}}"
ChName: "{{ with slicestr .Name 4 }}{{replace . "-" " "  | strings.TrimLeft " " | title }}{{end}}"
EnrollDate: {{ slicestr .Name 0 4 }}
Description: ""
ChDescription: ""
ResearchDir: "Deep Learning"
PersonAvatar: "/person/{{ with slicestr .Name 4 }}{{replace . "-" ""  | strings.TrimLeft " " | title }}{{end}}.jpg"
StudentType: "master"
---