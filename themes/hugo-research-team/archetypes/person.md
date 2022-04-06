---
PersonName: "{{ with slicestr .Name 10 }}{{replace . "-" " "  | strings.TrimLeft " " | title }}{{end}}"
EnrollDate: {{ slicestr .Name 0 10 }}
Description: ""
PersonAvatar: ""
---