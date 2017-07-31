# FlappyLight

> Jogo Arcade simples feito com Javascript!.

<a href="#"><img width="728" src="data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4KPCEtLSBHZW5lcmF0b3I6IEFkb2JlIElsbHVzdHJhdG9yIDIxLjAuMiwgU1ZHIEV4cG9ydCBQbHVnLUluIC4gU1ZHIFZlcnNpb246IDYuMDAgQnVpbGQgMCkgIC0tPgo8c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkNhbWFkYV8xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB4PSIwcHgiIHk9IjBweCIKCSB2aWV3Qm94PSIwIDAgMjA0OCAxMjYwIiBzdHlsZT0iZW5hYmxlLWJhY2tncm91bmQ6bmV3IDAgMCAyMDQ4IDEyNjA7IiB4bWw6c3BhY2U9InByZXNlcnZlIj4KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4KCS5zdDB7ZmlsbDojMDAyQjJGO30KCS5zdDF7ZmlsbDojRkZGRkZGO30KCS5zdDJ7ZmlsbDojMDBGRkZGO30KCS5zdDN7ZmlsbDojMjlBQkUyO30KPC9zdHlsZT4KPGc+Cgk8cmVjdCBjbGFzcz0ic3QwIiB3aWR0aD0iMjA0OCIgaGVpZ2h0PSIxMjYwIi8+CjwvZz4KPGc+Cgk8Zz4KCQk8cGF0aCBjbGFzcz0ic3QxIiBkPSJNMzcwLjMsOTAyLjF2LTMuM2MwLTAuNSwwLjItMC43LDAuNy0wLjdoMS4xYzAuNCwwLDAuNywwLjIsMC43LDAuN3YzLjJjMCwyLjgsMC43LDQuOSwyLjIsNi41CgkJCWMxLjUsMS42LDMuNiwyLjQsNi4zLDIuNGg5LjhjMi43LDAsNC44LTAuOCw2LjMtMi40YzEuNS0xLjYsMi4yLTMuOCwyLjItNi41di00LjFjMC0yLjYtMS00LjYtMy02LjFjLTItMS41LTQuNC0yLjYtNy4zLTMuMwoJCQljLTIuOS0wLjctNS43LTEuNC04LjYtMmMtMi45LTAuNy01LjMtMS44LTcuMy0zLjRjLTItMS42LTMtMy43LTMtNi40di00LjljMC0zLjQsMS02LjEsMy04LjFjMi0yLDQuNi0zLDgtM2g5LjhjMy4zLDAsNiwxLDgsMwoJCQljMiwyLDMsNC43LDMsOC4xdjIuNGMwLDAuNS0wLjIsMC43LTAuNywwLjdoLTEuMWMtMC40LDAtMC43LTAuMi0wLjctMC43di0yLjRjMC0yLjgtMC43LTQuOS0yLjItNi41Yy0xLjUtMS42LTMuNi0yLjQtNi4zLTIuNAoJCQloLTkuOGMtMi43LDAtNC44LDAuOC02LjMsMi40Yy0xLjUsMS42LTIuMiwzLjgtMi4yLDYuNXY0LjdjMCw0LDMuNCw2LjgsMTAuMyw4LjNjMi45LDAuNiw1LjgsMS4zLDguNiwyYzIuOSwwLjcsNS4zLDIsNy4zLDMuOAoJCQljMiwxLjgsMyw0LjEsMyw3LjF2NC4zYzAsMy40LTEsNi4xLTMsOC4xYy0yLDItNC42LDMtOCwzaC05LjhjLTMuMywwLTYtMS04LTNDMzcxLjMsOTA4LjEsMzcwLjMsOTA1LjQsMzcwLjMsOTAyLjF6Ii8+CgkJPHBhdGggY2xhc3M9InN0MSIgZD0iTTQxNi4yLDg2NC44di04LjFjMC0wLjUsMC4yLTAuNywwLjctMC43aDEuMWMwLjQsMCwwLjcsMC4yLDAuNywwLjd2OC4xYzAsMC41LTAuMiwwLjctMC43LDAuN2gtMS4xCgkJCUM0MTYuNCw4NjUuNSw0MTYuMiw4NjUuMyw0MTYuMiw4NjQuOHogTTQxNi4yLDkxMi40di00MC4xYzAtMC41LDAuMi0wLjcsMC43LTAuN2gxLjFjMC40LDAsMC43LDAuMiwwLjcsMC43djQwLjEKCQkJYzAsMC41LTAuMiwwLjctMC43LDAuN2gtMS4xQzQxNi40LDkxMy4yLDQxNi4yLDkxMi45LDQxNi4yLDkxMi40eiIvPgoJCTxwYXRoIGNsYXNzPSJzdDEiIGQ9Ik00MzMuOSw5MTMuMmgtMS4xYy0wLjQsMC0wLjctMC4yLTAuNy0wLjd2LTQwLjFjMC0wLjUsMC4yLTAuNywwLjctMC43aDEuMWMwLjQsMCwwLjcsMC4yLDAuNywwLjd2My41aDAuMwoJCQljMS41LTIuOCw0LjQtNC4yLDguNi00LjJoMy42YzQuOCwwLDguMSwxLjksOS45LDUuOGMwLjgtMS45LDIuMi0zLjMsNC4yLTQuM3M0LjEtMS41LDYuMi0xLjVoMy4zYzMuMywwLDYsMSw4LDNjMiwyLDMsNC43LDMsOC4xCgkJCXYyOS44YzAsMC41LTAuMiwwLjctMC43LDAuN2gtMS4xYy0wLjQsMC0wLjctMC4yLTAuNy0wLjd2LTI5LjdjMC0yLjgtMC43LTQuOS0yLjItNi41Yy0xLjUtMS42LTMuNi0yLjQtNi4zLTIuNGgtMy4zCgkJCWMtMi44LDAtNSwwLjgtNi43LDIuNGMtMS43LDEuNi0yLjYsMy44LTIuNiw2LjV2MjkuN2MwLDAuNS0wLjIsMC43LTAuNywwLjdoLTEuMWMtMC40LDAtMC43LTAuMi0wLjctMC43di0yOS43CgkJCWMwLTIuOC0wLjctNC45LTIuMi02LjVzLTMuNi0yLjQtNi4zLTIuNGgtMy40Yy0yLjcsMC00LjksMC43LTYuNiwyLjJjLTEuNywxLjUtMi41LDMuNi0yLjUsNi4zdjMwLjEKCQkJQzQzNC42LDkxMi45LDQzNC40LDkxMy4yLDQzMy45LDkxMy4yeiIvPgoJCTxwYXRoIGNsYXNzPSJzdDEiIGQ9Ik00OTYsOTI1LjZoLTEuMWMtMC40LDAtMC43LTAuMi0wLjctMC43di01Mi42YzAtMC41LDAuMi0wLjcsMC43LTAuN2gxLjFjMC40LDAsMC43LDAuMiwwLjcsMC43djMuNWgwLjMKCQkJYzEuNS0yLjgsNC40LTQuMiw4LjYtNC4yaDZjMy4zLDAsNiwxLDgsM2MyLDIsMyw0LjcsMyw4LjF2MTkuNGMwLDMuNC0xLDYuMS0zLDguMWMtMiwyLTQuNiwzLTgsM2gtNmMtNC4yLDAtNy4xLTEuNC04LjYtNC4yaC0wLjMKCQkJdjE2QzQ5Ni42LDkyNS40LDQ5Ni40LDkyNS42LDQ5Niw5MjUuNnogTTUwNS44LDkxMC45aDUuOWMyLjcsMCw0LjgtMC44LDYuMy0yLjRjMS41LTEuNiwyLjItMy44LDIuMi02LjV2LTE5LjMKCQkJYzAtMi44LTAuNy00LjktMi4yLTYuNWMtMS41LTEuNi0zLjYtMi40LTYuMy0yLjRoLTUuOWMtMi43LDAtNC45LDAuNy02LjYsMi4yYy0xLjcsMS41LTIuNSwzLjYtMi41LDYuM3YyMC4xCgkJCWMwLDIuNywwLjgsNC44LDIuNSw2LjNDNTAwLjksOTEwLjEsNTAzLjEsOTEwLjksNTA1LjgsOTEwLjl6Ii8+CgkJPHBhdGggY2xhc3M9InN0MSIgZD0iTTUzNyw5MTMuMmgtMS4xYy0wLjQsMC0wLjctMC4yLTAuNy0wLjd2LTU1LjljMC0wLjUsMC4yLTAuNywwLjctMC43aDEuMWMwLjQsMCwwLjcsMC4yLDAuNywwLjd2NTUuOQoJCQlDNTM3LjcsOTEyLjksNTM3LjUsOTEzLjIsNTM3LDkxMy4yeiIvPgoJCTxwYXRoIGNsYXNzPSJzdDEiIGQ9Ik01NzgsOTEzLjJoLTE2LjdjLTMuMywwLTYtMS04LTNjLTItMi0zLTQuNy0zLTguMXYtMTkuNGMwLTMuNCwxLTYuMSwzLTguMWMyLTIsNC42LTMsOC0zaDcuMmMzLjMsMCw2LDEsOCwzCgkJCWMyLDIsMyw0LjcsMyw4LjFWODkzYzAsMC41LTAuMiwwLjgtMC43LDAuOGgtMjUuMWMtMC41LDAtMC43LDAuMi0wLjcsMC43djcuNWMwLDIuOCwwLjcsNC45LDIuMiw2LjVjMS41LDEuNiwzLjYsMi40LDYuMywyLjRINTc4CgkJCWMwLjUsMCwwLjcsMC4yLDAuNywwLjd2MUM1NzguNyw5MTIuOSw1NzguNSw5MTMuMiw1NzgsOTEzLjJ6IE01NTMuNSw4OTEuNWgyMi43YzAuNSwwLDAuNy0wLjIsMC43LTAuN3YtOC4yCgkJCWMwLTIuOC0wLjctNC45LTIuMi02LjVzLTMuNi0yLjQtNi4zLTIuNGgtNy4yYy0yLjcsMC00LjgsMC44LTYuMywyLjRzLTIuMiwzLjgtMi4yLDYuNXY4LjJDNTUyLjgsODkxLjMsNTUzLDg5MS41LDU1My41LDg5MS41eiIKCQkJLz4KCQk8cGF0aCBjbGFzcz0ic3QxIiBkPSJNNjExLjcsOTEzLjJoLTEuMWMtMC41LDAtMC43LTAuMi0wLjUtMC43bDE3LjEtNTFjMC4yLTAuNSwwLjQtMC43LDAuOC0wLjdoMmMwLjQsMCwwLjcsMC4yLDAuOCwwLjdsMTcuMSw1MQoJCQljMC4yLDAuNSwwLDAuNy0wLjUsMC43aC0xLjJjLTAuNCwwLTAuNy0wLjItMC44LTAuN2wtNS0xNC4yaC0yMi44bC01LDE0LjJDNjEyLjMsOTEyLjksNjEyLDkxMy4yLDYxMS43LDkxMy4yeiBNNjI4LjgsODYzLjgKCQkJbC0xMC40LDMyaDIxbC0xMC40LTMySDYyOC44eiIvPgoJCTxwYXRoIGNsYXNzPSJzdDEiIGQ9Ik02NTguNyw5MTMuMmgtMS4xYy0wLjQsMC0wLjctMC4yLTAuNy0wLjd2LTQwLjFjMC0wLjUsMC4yLTAuNywwLjctMC43aDEuMWMwLjQsMCwwLjcsMC4yLDAuNywwLjd2My43aDAuMwoJCQljMC42LTEuMSwxLjYtMi4xLDMuMS0zYzEuNS0wLjksMy40LTEuNCw1LjgtMS40aDMuM2MwLjUsMCwwLjcsMC4yLDAuNywwLjd2MWMwLDAuNC0wLjIsMC43LTAuNywwLjdoLTMuM2MtMi44LDAtNSwwLjktNi43LDIuNgoJCQljLTEuNywxLjctMi41LDQuMS0yLjUsNy4xdjI4LjlDNjU5LjQsOTEyLjksNjU5LjEsOTEzLjIsNjU4LjcsOTEzLjJ6Ii8+CgkJPHBhdGggY2xhc3M9InN0MSIgZD0iTTcwNC4xLDkxMS41djFjMCwwLjQtMC4yLDAuNy0wLjcsMC43aC0xMS42Yy0zLjMsMC02LTEtOC0zYy0yLTItMy00LjctMy04LjF2LTE5LjRjMC0zLjQsMS02LjEsMy04LjEKCQkJYzItMiw0LjYtMyw4LTNoMTEuNmMwLjUsMCwwLjcsMC4yLDAuNywwLjd2MWMwLDAuNC0wLjIsMC43LTAuNywwLjdoLTExLjZjLTIuNywwLTQuOCwwLjgtNi4zLDIuNHMtMi4yLDMuOC0yLjIsNi41VjkwMgoJCQljMCwyLjgsMC43LDQuOSwyLjIsNi41YzEuNSwxLjYsMy42LDIuNCw2LjMsMi40aDExLjZDNzAzLjgsOTEwLjksNzA0LjEsOTExLjEsNzA0LjEsOTExLjV6Ii8+CgkJPHBhdGggY2xhc3M9InN0MSIgZD0iTTcyOS42LDkxMy4yaC02Yy0zLjMsMC02LTEtOC0zYy0yLTItMy00LjctMy04LjF2LTE5LjRjMC0zLjQsMS02LjEsMy04LjFjMi0yLDQuNi0zLDgtM2gxNi44CgkJCWMwLjQsMCwwLjcsMC4yLDAuNywwLjd2NDAuMWMwLDAuNS0wLjIsMC43LTAuNywwLjdoLTEuMWMtMC40LDAtMC43LTAuMi0wLjctMC43di0zLjVoLTAuM0M3MzYuNyw5MTEuNyw3MzMuOCw5MTMuMiw3MjkuNiw5MTMuMnoKCQkJIE03MzguNiw5MDIuNHYtMjcuOWMwLTAuNC0wLjItMC43LTAuNy0wLjdoLTE0LjNjLTIuNywwLTQuOCwwLjgtNi4zLDIuNHMtMi4yLDMuOC0yLjIsNi41VjkwMmMwLDIuOCwwLjcsNC45LDIuMiw2LjUKCQkJYzEuNSwxLjYsMy42LDIuNCw2LjMsMi40aDUuOWMyLjcsMCw0LjktMC43LDYuNi0yLjJDNzM3LjcsOTA3LjIsNzM4LjYsOTA1LjEsNzM4LjYsOTAyLjR6Ii8+CgkJPHBhdGggY2xhc3M9InN0MSIgZD0iTTc3MC4yLDkxMy4yaC02Yy0zLjMsMC02LTEtOC0zYy0yLTItMy00LjctMy04LjF2LTE5LjRjMC0zLjQsMS02LjEsMy04LjFjMi0yLDQuNi0zLDgtM2g2CgkJCWM0LjIsMCw3LjEsMS40LDguNiw0LjJoMC4zdi0xOS4zYzAtMC41LDAuMi0wLjcsMC43LTAuN2gxLjFjMC40LDAsMC43LDAuMiwwLjcsMC43djU1LjljMCwwLjUtMC4yLDAuNy0wLjcsMC43aC0xLjEKCQkJYy0wLjQsMC0wLjctMC4yLTAuNy0wLjd2LTMuNWgtMC4zQzc3Ny4zLDkxMS43LDc3NC41LDkxMy4yLDc3MC4yLDkxMy4yeiBNNzc5LjIsOTAyLjR2LTIwLjFjMC0yLjctMC44LTQuOC0yLjUtNi4zCgkJCWMtMS43LTEuNS0zLjktMi4yLTYuNi0yLjJoLTUuOWMtMi43LDAtNC44LDAuOC02LjMsMi40cy0yLjIsMy44LTIuMiw2LjVWOTAyYzAsMi44LDAuNyw0LjksMi4yLDYuNWMxLjUsMS42LDMuNiwyLjQsNi4zLDIuNGg1LjkKCQkJYzIuNywwLDQuOS0wLjcsNi42LTIuMkM3NzguMyw5MDcuMiw3NzkuMiw5MDUuMSw3NzkuMiw5MDIuNHoiLz4KCQk8cGF0aCBjbGFzcz0ic3QxIiBkPSJNODIxLjUsOTEzLjJoLTE2LjdjLTMuMywwLTYtMS04LTNjLTItMi0zLTQuNy0zLTguMXYtMTkuNGMwLTMuNCwxLTYuMSwzLTguMWMyLTIsNC42LTMsOC0zaDcuMgoJCQljMy4zLDAsNiwxLDgsM2MyLDIsMyw0LjcsMyw4LjFWODkzYzAsMC41LTAuMiwwLjgtMC43LDAuOEg3OTdjLTAuNSwwLTAuNywwLjItMC43LDAuN3Y3LjVjMCwyLjgsMC43LDQuOSwyLjIsNi41CgkJCWMxLjUsMS42LDMuNiwyLjQsNi4zLDIuNGgxNi43YzAuNSwwLDAuNywwLjIsMC43LDAuN3YxQzgyMi4zLDkxMi45LDgyMiw5MTMuMiw4MjEuNSw5MTMuMnogTTc5Nyw4OTEuNWgyMi43CgkJCWMwLjUsMCwwLjctMC4yLDAuNy0wLjd2LTguMmMwLTIuOC0wLjctNC45LTIuMi02LjVzLTMuNi0yLjQtNi4zLTIuNGgtNy4yYy0yLjcsMC00LjgsMC44LTYuMywyLjRzLTIuMiwzLjgtMi4yLDYuNXY4LjIKCQkJQzc5Ni4zLDg5MS4zLDc5Ni42LDg5MS41LDc5Nyw4OTEuNXoiLz4KCQk8cGF0aCBjbGFzcz0ic3QxIiBkPSJNODc3LjUsOTEzLjJoLTljLTMuMywwLTYtMS04LTNjLTItMi0zLTQuNy0zLTguMXYtMzAuM2MwLTMuNCwxLTYuMSwzLTguMWMyLTIsNC42LTMsOC0zaDljMy4zLDAsNiwxLDgsMwoJCQljMiwyLDMsNC43LDMsOC4xdjQuMWMwLDAuNS0wLjIsMC43LTAuNywwLjdoLTEuMWMtMC40LDAtMC43LTAuMi0wLjctMC43di00YzAtMi44LTAuNy00LjktMi4yLTYuNWMtMS41LTEuNi0zLjYtMi40LTYuMy0yLjRoLTkKCQkJYy0yLjcsMC00LjgsMC44LTYuMywyLjRjLTEuNSwxLjYtMi4yLDMuOC0yLjIsNi41VjkwMmMwLDIuOCwwLjcsNC45LDIuMiw2LjVjMS41LDEuNiwzLjYsMi40LDYuMywyLjRoOWMyLjcsMCw0LjgtMC44LDYuMy0yLjQKCQkJYzEuNS0xLjYsMi4yLTMuOCwyLjItNi41di0xMi4zYzAtMC40LTAuMi0wLjctMC43LTAuN2gtMTAuNWMtMC41LDAtMC43LTAuMi0wLjctMC43di0xYzAtMC40LDAuMi0wLjcsMC43LTAuN2gxMi4yCgkJCWMxLDAsMS41LDAuNSwxLjUsMS41djEzLjhjMCwzLjQtMSw2LjEtMyw4LjFDODgzLjQsOTEyLjIsODgwLjgsOTEzLjIsODc3LjUsOTEzLjJ6Ii8+CgkJPHBhdGggY2xhc3M9InN0MSIgZD0iTTkxNy42LDkxMy4yaC02Yy0zLjMsMC02LTEtOC0zYy0yLTItMy00LjctMy04LjF2LTE5LjRjMC0zLjQsMS02LjEsMy04LjFjMi0yLDQuNi0zLDgtM2gxNi44CgkJCWMwLjQsMCwwLjcsMC4yLDAuNywwLjd2NDAuMWMwLDAuNS0wLjIsMC43LTAuNywwLjdoLTEuMWMtMC40LDAtMC43LTAuMi0wLjctMC43di0zLjVoLTAuM0M5MjQuNyw5MTEuNyw5MjEuOCw5MTMuMiw5MTcuNiw5MTMuMnoKCQkJIE05MjYuNiw5MDIuNHYtMjcuOWMwLTAuNC0wLjItMC43LTAuNy0wLjdoLTE0LjNjLTIuNywwLTQuOCwwLjgtNi4zLDIuNHMtMi4yLDMuOC0yLjIsNi41VjkwMmMwLDIuOCwwLjcsNC45LDIuMiw2LjUKCQkJYzEuNSwxLjYsMy42LDIuNCw2LjMsMi40aDUuOWMyLjcsMCw0LjktMC43LDYuNi0yLjJDOTI1LjcsOTA3LjIsOTI2LjYsOTA1LjEsOTI2LjYsOTAyLjR6Ii8+CgkJPHBhdGggY2xhc3M9InN0MSIgZD0iTTk0My45LDkxMy4yaC0xLjFjLTAuNCwwLTAuNy0wLjItMC43LTAuN3YtNDAuMWMwLTAuNSwwLjItMC43LDAuNy0wLjdoMS4xYzAuNCwwLDAuNywwLjIsMC43LDAuN3YzLjVoMC4zCgkJCWMxLjUtMi44LDQuNC00LjIsOC42LTQuMmgzLjZjNC44LDAsOC4xLDEuOSw5LjksNS44YzAuOC0xLjksMi4yLTMuMyw0LjItNC4zczQuMS0xLjUsNi4yLTEuNWgzLjNjMy4zLDAsNiwxLDgsM2MyLDIsMyw0LjcsMyw4LjEKCQkJdjI5LjhjMCwwLjUtMC4yLDAuNy0wLjcsMC43aC0xLjFjLTAuNCwwLTAuNy0wLjItMC43LTAuN3YtMjkuN2MwLTIuOC0wLjctNC45LTIuMi02LjVjLTEuNS0xLjYtMy42LTIuNC02LjMtMi40aC0zLjMKCQkJYy0yLjgsMC01LDAuOC02LjcsMi40Yy0xLjcsMS42LTIuNiwzLjgtMi42LDYuNXYyOS43YzAsMC41LTAuMiwwLjctMC43LDAuN2gtMS4xYy0wLjQsMC0wLjctMC4yLTAuNy0wLjd2LTI5LjcKCQkJYzAtMi44LTAuNy00LjktMi4yLTYuNXMtMy42LTIuNC02LjMtMi40aC0zLjRjLTIuNywwLTQuOSwwLjctNi42LDIuMmMtMS43LDEuNS0yLjUsMy42LTIuNSw2LjN2MzAuMQoJCQlDOTQ0LjUsOTEyLjksOTQ0LjMsOTEzLjIsOTQzLjksOTEzLjJ6Ii8+CgkJPHBhdGggY2xhc3M9InN0MSIgZD0iTTEwMzEsOTEzLjJoLTE2LjdjLTMuMywwLTYtMS04LTNjLTItMi0zLTQuNy0zLTguMXYtMTkuNGMwLTMuNCwxLTYuMSwzLTguMWMyLTIsNC42LTMsOC0zaDcuMmMzLjMsMCw2LDEsOCwzCgkJCWMyLDIsMyw0LjcsMyw4LjFWODkzYzAsMC41LTAuMiwwLjgtMC43LDAuOGgtMjUuMWMtMC41LDAtMC43LDAuMi0wLjcsMC43djcuNWMwLDIuOCwwLjcsNC45LDIuMiw2LjVjMS41LDEuNiwzLjYsMi40LDYuMywyLjQKCQkJaDE2LjdjMC41LDAsMC43LDAuMiwwLjcsMC43djFDMTAzMS43LDkxMi45LDEwMzEuNSw5MTMuMiwxMDMxLDkxMy4yeiBNMTAwNi41LDg5MS41aDIyLjdjMC41LDAsMC43LTAuMiwwLjctMC43di04LjIKCQkJYzAtMi44LTAuNy00LjktMi4yLTYuNXMtMy42LTIuNC02LjMtMi40aC03LjJjLTIuNywwLTQuOCwwLjgtNi4zLDIuNHMtMi4yLDMuOC0yLjIsNi41djguMkMxMDA1LjgsODkxLjMsMTAwNiw4OTEuNSwxMDA2LjUsODkxLjUKCQkJeiIvPgoJCTxwYXRoIGNsYXNzPSJzdDEiIGQ9Ik0xMDgzLjYsOTEzLjJoLTZjLTMuMywwLTYtMS04LTNjLTItMi0zLTQuNy0zLTguMXYtMjkuOGMwLTAuNSwwLjItMC43LDAuNy0wLjdoMS4xYzAuNCwwLDAuNywwLjIsMC43LDAuNwoJCQlWOTAyYzAsMi44LDAuNyw0LjksMi4yLDYuNWMxLjUsMS42LDMuNiwyLjQsNi4zLDIuNGg1LjljMi43LDAsNC45LTAuNyw2LjYtMi4yYzEuNy0xLjUsMi41LTMuNiwyLjUtNi4zdi0zMC4xCgkJCWMwLTAuNSwwLjItMC43LDAuNy0wLjdoMS4xYzAuNCwwLDAuNywwLjIsMC43LDAuN3Y0MC4xYzAsMC41LTAuMiwwLjctMC43LDAuN2gtMS4xYy0wLjQsMC0wLjctMC4yLTAuNy0wLjd2LTMuNWgtMC4zCgkJCUMxMDkwLjcsOTExLjcsMTA4Ny44LDkxMy4yLDEwODMuNiw5MTMuMnoiLz4KCQk8cGF0aCBjbGFzcz0ic3QxIiBkPSJNMTEyMC45LDkxMy4yaC0xMy45Yy0wLjUsMC0wLjctMC4yLTAuNy0wLjd2LTFjMC0wLjQsMC4yLTAuNywwLjctMC43aDEzLjljNS41LDAsOC4yLTIuMiw4LjItNi41di0yLjQKCQkJYzAtMi0wLjQtMy42LTEuMS00LjljLTAuNy0xLjMtMi0yLjItMy44LTIuOWwtMTAuOC0zLjhjLTIuOC0xLTQuOC0yLjItNS45LTMuNmMtMS4xLTEuNC0xLjctMy41LTEuNy02LjFjMC02LjEsMy4zLTkuMSwxMC05LjEKCQkJaDEzLjFjMC41LDAsMC43LDAuMiwwLjcsMC43djFjMCwwLjQtMC4yLDAuNy0wLjcsMC43aC0xMy4xYy0yLjUsMC00LjQsMC42LTUuNiwxLjdzLTEuOCwyLjQtMS44LDMuOXYyLjJjMCwxLjcsMC40LDMuMSwxLjMsNAoJCQljMC45LDEsMi4zLDEuOCw0LjIsMi40bDEwLjcsMy44YzIuOSwwLjgsNC44LDIuMSw1LjYsNGMwLjksMS44LDEuMyw0LjQsMS4zLDcuN2MwLDMuMy0wLjksNS43LTIuNiw3LjIKCQkJQzExMjcuMyw5MTIuNCwxMTI0LjYsOTEzLjIsMTEyMC45LDkxMy4yeiIvPgoJCTxwYXRoIGNsYXNzPSJzdDEiIGQ9Ik0xMTQzLjUsODY0Ljh2LTguMWMwLTAuNSwwLjItMC43LDAuNy0wLjdoMS4xYzAuNCwwLDAuNywwLjIsMC43LDAuN3Y4LjFjMCwwLjUtMC4yLDAuNy0wLjcsMC43aC0xLjEKCQkJQzExNDMuNyw4NjUuNSwxMTQzLjUsODY1LjMsMTE0My41LDg2NC44eiBNMTE0My41LDkxMi40di00MC4xYzAtMC41LDAuMi0wLjcsMC43LTAuN2gxLjFjMC40LDAsMC43LDAuMiwwLjcsMC43djQwLjEKCQkJYzAsMC41LTAuMiwwLjctMC43LDAuN2gtMS4xQzExNDMuNyw5MTMuMiwxMTQzLjUsOTEyLjksMTE0My41LDkxMi40eiIvPgoJCTxwYXRoIGNsYXNzPSJzdDEiIGQ9Ik0xMTYxLjIsOTEzLjJoLTEuMWMtMC40LDAtMC43LTAuMi0wLjctMC43di00MC4xYzAtMC41LDAuMi0wLjcsMC43LTAuN2gxLjFjMC40LDAsMC43LDAuMiwwLjcsMC43djMuNWgwLjMKCQkJYzEuNS0yLjgsNC40LTQuMiw4LjYtNC4yaDZjMy4zLDAsNiwxLDgsM2MyLDIsMyw0LjcsMyw4LjF2MjkuOGMwLDAuNS0wLjIsMC43LTAuNywwLjdoLTEuMWMtMC40LDAtMC43LTAuMi0wLjctMC43di0yOS43CgkJCWMwLTIuOC0wLjctNC45LTIuMi02LjVjLTEuNS0xLjYtMy42LTIuNC02LjMtMi40aC01LjljLTIuNywwLTQuOSwwLjctNi42LDIuMmMtMS43LDEuNS0yLjUsMy42LTIuNSw2LjN2MzAuMQoJCQlDMTE2MS44LDkxMi45LDExNjEuNiw5MTMuMiwxMTYxLjIsOTEzLjJ6Ii8+CgkJPHBhdGggY2xhc3M9InN0MSIgZD0iTTEyMTYuOSw5MTAuN2gtNmMtMy4zLDAtNi0xLTgtM2MtMi0yLTMtNC43LTMtOC4xdi0xN2MwLTMuNCwxLTYuMSwzLTguMWMyLTIsNC42LTMsOC0zaDE2LjgKCQkJYzAuNCwwLDAuNywwLjIsMC43LDAuN3Y0MC42YzAsMy40LTEsNi4xLTMsOC4xYy0yLDItNC42LDMtOCwzaC0xNC42Yy0wLjUsMC0wLjctMC4yLTAuNy0wLjd2LTFjMC0wLjQsMC4yLTAuNywwLjctMC43aDE0LjYKCQkJYzIuNywwLDQuOC0wLjgsNi4zLTIuNGMxLjUtMS42LDIuMi0zLjgsMi4yLTYuNXYtNi40aC0wLjNDMTIyNC4xLDkwOS4zLDEyMjEuMiw5MTAuNywxMjE2LjksOTEwLjd6IE0xMjI1LjksODk5Ljl2LTI1LjQKCQkJYzAtMC40LTAuMi0wLjctMC43LTAuN2gtMTQuM2MtMi43LDAtNC44LDAuOC02LjMsMi40cy0yLjIsMy44LTIuMiw2LjV2MTYuOGMwLDIuOCwwLjcsNC45LDIuMiw2LjVzMy42LDIuNCw2LjMsMi40aDUuOQoJCQljMi43LDAsNC45LTAuNyw2LjYtMi4yQzEyMjUuMSw5MDQuOCwxMjI1LjksOTAyLjcsMTIyNS45LDg5OS45eiIvPgoJCTxwYXRoIGNsYXNzPSJzdDEiIGQ9Ik0xMjg5LjIsODYwLjdoMS4xYzAuNCwwLDAuNywwLjIsMC43LDAuN3Y0MC43YzAsMy40LTEsNi4xLTMsOC4xYy0yLDItNC42LDMtOCwzaC04LjJjLTMuMywwLTYtMS04LTMKCQkJYy0yLTItMy00LjctMy04LjF2LTYuNWMwLTAuNSwwLjItMC43LDAuNy0wLjdoMS4xYzAuNCwwLDAuNywwLjIsMC43LDAuN3Y2LjRjMCwyLjgsMC43LDQuOSwyLjIsNi41YzEuNSwxLjYsMy42LDIuNCw2LjMsMi40aDguMgoJCQljMi43LDAsNC44LTAuOCw2LjMtMi40YzEuNS0xLjYsMi4yLTMuOCwyLjItNi41di00MC41QzEyODguNiw4NjEsMTI4OC44LDg2MC43LDEyODkuMiw4NjAuN3oiLz4KCQk8cGF0aCBjbGFzcz0ic3QxIiBkPSJNMTMwNS4zLDkwMi4xdi0zLjNjMC0wLjUsMC4yLTAuNywwLjctMC43aDEuMWMwLjQsMCwwLjcsMC4yLDAuNywwLjd2My4yYzAsMi44LDAuNyw0LjksMi4yLDYuNQoJCQljMS41LDEuNiwzLjYsMi40LDYuMywyLjRoOS44YzIuNywwLDQuOC0wLjgsNi4zLTIuNGMxLjUtMS42LDIuMi0zLjgsMi4yLTYuNXYtNC4xYzAtMi42LTEtNC42LTMtNi4xYy0yLTEuNS00LjQtMi42LTcuMy0zLjMKCQkJYy0yLjktMC43LTUuNy0xLjQtOC42LTJjLTIuOS0wLjctNS4zLTEuOC03LjMtMy40cy0zLTMuNy0zLTYuNHYtNC45YzAtMy40LDEtNi4xLDMtOC4xYzItMiw0LjYtMyw4LTNoOS44YzMuMywwLDYsMSw4LDMKCQkJYzIsMiwzLDQuNywzLDguMXYyLjRjMCwwLjUtMC4yLDAuNy0wLjcsMC43aC0xLjFjLTAuNCwwLTAuNy0wLjItMC43LTAuN3YtMi40YzAtMi44LTAuNy00LjktMi4yLTYuNWMtMS41LTEuNi0zLjYtMi40LTYuMy0yLjQKCQkJaC05LjhjLTIuNywwLTQuOCwwLjgtNi4zLDIuNGMtMS41LDEuNi0yLjIsMy44LTIuMiw2LjV2NC43YzAsNCwzLjQsNi44LDEwLjMsOC4zYzIuOSwwLjYsNS44LDEuMyw4LjYsMmMyLjksMC43LDUuMywyLDcuMywzLjgKCQkJYzIsMS44LDMsNC4xLDMsNy4xdjQuM2MwLDMuNC0xLDYuMS0zLDguMWMtMiwyLTQuNiwzLTgsM2gtOS44Yy0zLjMsMC02LTEtOC0zQzEzMDYuMyw5MDguMSwxMzA1LjMsOTA1LjQsMTMwNS4zLDkwMi4xeiIvPgoJCTxwYXRoIGNsYXNzPSJzdDEiIGQ9Ik0xMzkxLjUsOTEzLjJoLTYuOWMtMy4zLDAtNi0xLTgtMi45Yy0yLTEuOS0zLTQuNi0zLTh2LTcuNWMwLTIuNywwLjctNS4xLDIuMS03LjFjMS40LTIsMy42LTMsNi42LTMuMQoJCQljLTIuNi0zLjEtMy45LTYuMy0zLjktOS42di0zLjVjMC0zLjQsMS02LDMtOGMyLTEuOSw0LjYtMi45LDgtMi45aDEuOGMzLjMsMCw2LDEsOCwyLjljMiwxLjksMyw0LjYsMyw4djRjMCwwLjUtMC4yLDAuNy0wLjcsMC43CgkJCWgtMS4xYy0wLjQsMC0wLjctMC4yLTAuNy0wLjd2LTMuOWMwLTIuOC0wLjctNC45LTIuMi02LjRjLTEuNS0xLjUtMy42LTIuMi02LjMtMi4yaC0xLjhjLTIuNywwLTQuOCwwLjctNi4zLDIuMgoJCQljLTEuNSwxLjUtMi4yLDMuNi0yLjIsNi40djMuM2MwLDEuOCwwLjIsMy4zLDAuNyw0LjVzMS40LDIuNiwyLjgsNGw1LjUsNi4zaDE5LjljMC41LDAsMC43LDAuMiwwLjcsMC43djFjMCwwLjQtMC4yLDAuNy0wLjcsMC43CgkJCWgtMTcuOWwxNy44LDIwLjZjMC4xLDAuMiwwLjEsMC40LTAuMiwwLjVoLTEuNWMtMC40LDAtMC43LTAuMi0xLjEtMC41bC01LjEtNS45Yy0wLjcsMi0yLDMuNi0zLjgsNC43CgkJCUMxMzk2LjEsOTEyLjYsMTM5NCw5MTMuMiwxMzkxLjUsOTEzLjJ6IE0xMzg0LjYsOTEwLjloNi45YzQuNywwLDcuNS0yLjEsOC4yLTYuM2wtMTYtMTguNGMtMi41LDAuMi00LjQsMS01LjcsMi41CgkJCWMtMS4zLDEuNS0yLDMuNS0yLDYuMnY3LjNjMCwyLjgsMC43LDQuOSwyLjIsNi40QzEzNzkuNyw5MTAuMSwxMzgxLjgsOTEwLjksMTM4NC42LDkxMC45eiIvPgoJCTxwYXRoIGNsYXNzPSJzdDEiIGQ9Ik0xNDQyLjQsOTEzLjJoLTEuMWMtMC41LDAtMC43LTAuMi0wLjUtMC43bDE3LjEtNTFjMC4yLTAuNSwwLjQtMC43LDAuOC0wLjdoMmMwLjQsMCwwLjcsMC4yLDAuOCwwLjdsMTcuMSw1MQoJCQljMC4yLDAuNSwwLDAuNy0wLjUsMC43aC0xLjJjLTAuNCwwLTAuNy0wLjItMC44LTAuN2wtNS0xNC4yaC0yMi44bC01LDE0LjJDMTQ0My4xLDkxMi45LDE0NDIuOCw5MTMuMiwxNDQyLjQsOTEzLjJ6CgkJCSBNMTQ1OS41LDg2My44bC0xMC40LDMyaDIxbC0xMC40LTMySDE0NTkuNXoiLz4KCQk8cGF0aCBjbGFzcz0ic3QxIiBkPSJNMTQ4OS40LDkxMy4yaC0xLjFjLTAuNCwwLTAuNy0wLjItMC43LTAuN3YtNDAuMWMwLTAuNSwwLjItMC43LDAuNy0wLjdoMS4xYzAuNCwwLDAuNywwLjIsMC43LDAuN3YzLjdoMC4zCgkJCWMwLjYtMS4xLDEuNi0yLjEsMy4xLTNjMS41LTAuOSwzLjQtMS40LDUuOC0xLjRoMy4zYzAuNSwwLDAuNywwLjIsMC43LDAuN3YxYzAsMC40LTAuMiwwLjctMC43LDAuN2gtMy4zYy0yLjgsMC01LDAuOS02LjcsMi42CgkJCWMtMS43LDEuNy0yLjUsNC4xLTIuNSw3LjF2MjguOUMxNDkwLjEsOTEyLjksMTQ4OS45LDkxMy4yLDE0ODkuNCw5MTMuMnoiLz4KCQk8cGF0aCBjbGFzcz0ic3QxIiBkPSJNMTUyOC41LDkxMy4yaC02Yy0zLjMsMC02LTEtOC0zYy0yLTItMy00LjctMy04LjF2LTE5LjRjMC0zLjQsMS02LjEsMy04LjFjMi0yLDQuNi0zLDgtM2g2CgkJCWM0LjIsMCw3LjEsMS40LDguNiw0LjJoMC4zdi0xOS4zYzAtMC41LDAuMi0wLjcsMC43LTAuN2gxLjFjMC40LDAsMC43LDAuMiwwLjcsMC43djU1LjljMCwwLjUtMC4yLDAuNy0wLjcsMC43aC0xLjEKCQkJYy0wLjQsMC0wLjctMC4yLTAuNy0wLjd2LTMuNWgtMC4zQzE1MzUuNiw5MTEuNywxNTMyLjgsOTEzLjIsMTUyOC41LDkxMy4yeiBNMTUzNy41LDkwMi40di0yMC4xYzAtMi43LTAuOC00LjgtMi41LTYuMwoJCQljLTEuNy0xLjUtMy45LTIuMi02LjYtMi4yaC01LjljLTIuNywwLTQuOCwwLjgtNi4zLDIuNHMtMi4yLDMuOC0yLjIsNi41VjkwMmMwLDIuOCwwLjcsNC45LDIuMiw2LjVjMS41LDEuNiwzLjYsMi40LDYuMywyLjRoNS45CgkJCWMyLjcsMCw0LjktMC43LDYuNi0yLjJDMTUzNi42LDkwNy4yLDE1MzcuNSw5MDUuMSwxNTM3LjUsOTAyLjR6Ii8+CgkJPHBhdGggY2xhc3M9InN0MSIgZD0iTTE1NjkuNSw5MTMuMmgtNmMtMy4zLDAtNi0xLTgtM2MtMi0yLTMtNC43LTMtOC4xdi0yOS44YzAtMC41LDAuMi0wLjcsMC43LTAuN2gxLjFjMC40LDAsMC43LDAuMiwwLjcsMC43CgkJCVY5MDJjMCwyLjgsMC43LDQuOSwyLjIsNi41YzEuNSwxLjYsMy42LDIuNCw2LjMsMi40aDUuOWMyLjcsMCw0LjktMC43LDYuNi0yLjJjMS43LTEuNSwyLjUtMy42LDIuNS02LjN2LTMwLjEKCQkJYzAtMC41LDAuMi0wLjcsMC43LTAuN2gxLjFjMC40LDAsMC43LDAuMiwwLjcsMC43djQwLjFjMCwwLjUtMC4yLDAuNy0wLjcsMC43aC0xLjFjLTAuNCwwLTAuNy0wLjItMC43LTAuN3YtMy41aC0wLjMKCQkJQzE1NzYuNyw5MTEuNywxNTczLjgsOTEzLjIsMTU2OS41LDkxMy4yeiIvPgoJCTxwYXRoIGNsYXNzPSJzdDEiIGQ9Ik0xNTk0LjQsODY0Ljh2LTguMWMwLTAuNSwwLjItMC43LDAuNy0wLjdoMS4xYzAuNCwwLDAuNywwLjIsMC43LDAuN3Y4LjFjMCwwLjUtMC4yLDAuNy0wLjcsMC43aC0xLjEKCQkJQzE1OTQuNiw4NjUuNSwxNTk0LjQsODY1LjMsMTU5NC40LDg2NC44eiBNMTU5NC40LDkxMi40di00MC4xYzAtMC41LDAuMi0wLjcsMC43LTAuN2gxLjFjMC40LDAsMC43LDAuMiwwLjcsMC43djQwLjEKCQkJYzAsMC41LTAuMiwwLjctMC43LDAuN2gtMS4xQzE1OTQuNiw5MTMuMiwxNTk0LjQsOTEyLjksMTU5NC40LDkxMi40eiIvPgoJCTxwYXRoIGNsYXNzPSJzdDEiIGQ9Ik0xNjEyLjEsOTEzLjJoLTEuMWMtMC40LDAtMC43LTAuMi0wLjctMC43di00MC4xYzAtMC41LDAuMi0wLjcsMC43LTAuN2gxLjFjMC40LDAsMC43LDAuMiwwLjcsMC43djMuNWgwLjMKCQkJYzEuNS0yLjgsNC40LTQuMiw4LjYtNC4yaDZjMy4zLDAsNiwxLDgsM2MyLDIsMyw0LjcsMyw4LjF2MjkuOGMwLDAuNS0wLjIsMC43LTAuNywwLjdoLTEuMWMtMC40LDAtMC43LTAuMi0wLjctMC43di0yOS43CgkJCWMwLTIuOC0wLjctNC45LTIuMi02LjVjLTEuNS0xLjYtMy42LTIuNC02LjMtMi40aC01LjljLTIuNywwLTQuOSwwLjctNi42LDIuMmMtMS43LDEuNS0yLjUsMy42LTIuNSw2LjN2MzAuMQoJCQlDMTYxMi44LDkxMi45LDE2MTIuNiw5MTMuMiwxNjEyLjEsOTEzLjJ6Ii8+CgkJPHBhdGggY2xhc3M9InN0MSIgZD0iTTE2NjguNCw5MTMuMmgtNi45Yy0zLjMsMC02LTEtOC0zYy0yLTItMy00LjctMy04LjF2LTE5LjRjMC0zLjQsMS02LjEsMy04LjFjMi0yLDQuNi0zLDgtM2g2LjkKCQkJYzMuMywwLDYsMSw4LDNjMiwyLDMsNC43LDMsOC4xdjE5LjRjMCwzLjQtMSw2LjEtMyw4LjFDMTY3NC40LDkxMi4yLDE2NzEuNyw5MTMuMiwxNjY4LjQsOTEzLjJ6IE0xNjYxLjUsOTEwLjloNi45CgkJCWMyLjcsMCw0LjgtMC44LDYuMy0yLjRjMS41LTEuNiwyLjItMy44LDIuMi02LjV2LTE5LjNjMC0yLjgtMC43LTQuOS0yLjItNi41Yy0xLjUtMS42LTMuNi0yLjQtNi4zLTIuNGgtNi45CgkJCWMtMi43LDAtNC44LDAuOC02LjMsMi40Yy0xLjUsMS42LTIuMiwzLjgtMi4yLDYuNVY5MDJjMCwyLjgsMC43LDQuOSwyLjIsNi41QzE2NTYuNyw5MTAuMSwxNjU4LjcsOTEwLjksMTY2MS41LDkxMC45eiIvPgoJPC9nPgo8L2c+CjxnPgoJPGc+CgkJPGc+CgkJCTxwYXRoIGNsYXNzPSJzdDEiIGQ9Ik02NzguNyw3MzUuOGgtMi4yYy0wLjgsMC0xLjItMC41LTEuMi0xLjR2LTk2LjljMC0wLjksMC40LTEuNCwxLjItMS40aDQ3LjNjMC45LDAsMS40LDAuNCwxLjQsMS4ydjEuOQoJCQkJYzAsMC44LTAuNSwxLjItMS40LDEuMmgtNDIuNWMtMC45LDAtMS40LDAuNC0xLjQsMS4ydjQxLjNjMCwwLjgsMC41LDEuMiwxLjQsMS4yaDM4LjNjMC45LDAsMS40LDAuNCwxLjQsMS4ydjEuOQoJCQkJYzAsMC44LTAuNSwxLjItMS40LDEuMmgtMzguM2MtMC45LDAtMS40LDAuNC0xLjQsMS4ydjQ0LjdDNjc5LjksNzM1LjMsNjc5LjUsNzM1LjgsNjc4LjcsNzM1Ljh6Ii8+CgkJCTxwYXRoIGNsYXNzPSJzdDEiIGQ9Ik03NDkuNSw3MzUuOGgtMi4yYy0wLjgsMC0xLjItMC41LTEuMi0xLjRWNjI4LjFjMC0wLjksMC40LTEuNCwxLjItMS40aDIuMmMwLjgsMCwxLjIsMC41LDEuMiwxLjR2MTA2LjIKCQkJCUM3NTAuOCw3MzUuMyw3NTAuNCw3MzUuOCw3NDkuNSw3MzUuOHoiLz4KCQkJPHBhdGggY2xhc3M9InN0MSIgZD0iTTgwNy4xLDczNS44aC0xMS41Yy02LjMsMC0xMS4zLTEuOS0xNS4xLTUuN2MtMy44LTMuOC01LjctOC45LTUuNy0xNS40di0zNi45YzAtNi40LDEuOS0xMS41LDUuNy0xNS40CgkJCQljMy44LTMuOCw4LjgtNS43LDE1LjEtNS43aDMyYzAuOCwwLDEuMiwwLjUsMS4yLDEuNHY3Ni4zYzAsMC45LTAuNCwxLjQtMS4yLDEuNGgtMi4yYy0wLjgsMC0xLjItMC41LTEuMi0xLjR2LTYuN2gtMC42CgkJCQlDODIwLjYsNzMzLjEsODE1LjIsNzM1LjgsODA3LjEsNzM1Ljh6IE04MjQuMiw3MTUuM3YtNTNjMC0wLjgtMC41LTEuMi0xLjQtMS4yaC0yNy4xYy01LjIsMC05LjIsMS41LTExLjksNC41CgkJCQljLTIuOCwzLTQuMiw3LjEtNC4yLDEyLjR2MzYuNmMwLDUuMywxLjQsOS40LDQuMiwxMi40YzIuOCwzLDYuOCw0LjUsMTEuOSw0LjVoMTEuMmM1LjIsMCw5LjQtMS40LDEyLjYtNC4yCgkJCQlDODIyLjUsNzI0LjQsODI0LjIsNzIwLjUsODI0LjIsNzE1LjN6Ii8+CgkJCTxwYXRoIGNsYXNzPSJzdDEiIGQ9Ik04NTcsNzU5LjVoLTIuMmMtMC44LDAtMS4yLTAuNS0xLjItMS40di0xMDBjMC0wLjksMC40LTEuNCwxLjItMS40aDIuMmMwLjgsMCwxLjIsMC41LDEuMiwxLjR2Ni43aDAuNgoJCQkJYzIuOS01LjQsOC40LTguMSwxNi40LTguMWgxMS41YzYuMywwLDExLjMsMS45LDE1LjEsNS43YzMuOCwzLjgsNS43LDguOSw1LjcsMTUuNHYzNi45YzAsNi40LTEuOSwxMS41LTUuNywxNS40CgkJCQljLTMuOCwzLjgtOC44LDUuNy0xNS4xLDUuN2gtMTEuNWMtOC4xLDAtMTMuNS0yLjctMTYuNC04LjFoLTAuNnYzMC40Qzg1OC4zLDc1OSw4NTcuOSw3NTkuNSw4NTcsNzU5LjV6IE04NzUuNiw3MzEuNGgxMS4yCgkJCQljNS4yLDAsOS4yLTEuNSwxMS45LTQuNWMyLjgtMyw0LjItNy4xLDQuMi0xMi40di0zNi42YzAtNS4zLTEuNC05LjQtNC4yLTEyLjRjLTIuOC0zLTYuOC00LjUtMTEuOS00LjVoLTExLjIKCQkJCWMtNS4yLDAtOS40LDEuNC0xMi42LDQuMmMtMy4yLDIuOC00LjgsNi44LTQuOCwxMS45djM4LjJjMCw1LjIsMS42LDkuMiw0LjgsMTEuOUM4NjYuMyw3MzAsODcwLjUsNzMxLjQsODc1LjYsNzMxLjR6Ii8+CgkJCTxwYXRoIGNsYXNzPSJzdDEiIGQ9Ik05MzQuMyw3NTkuNWgtMi4yYy0wLjgsMC0xLjItMC41LTEuMi0xLjR2LTEwMGMwLTAuOSwwLjQtMS40LDEuMi0xLjRoMi4yYzAuOCwwLDEuMiwwLjUsMS4yLDEuNHY2LjdoMC42CgkJCQljMi45LTUuNCw4LjQtOC4xLDE2LjQtOC4xaDExLjVjNi4zLDAsMTEuMywxLjksMTUuMSw1LjdjMy44LDMuOCw1LjcsOC45LDUuNywxNS40djM2LjljMCw2LjQtMS45LDExLjUtNS43LDE1LjQKCQkJCWMtMy44LDMuOC04LjgsNS43LTE1LjEsNS43aC0xMS41Yy04LjEsMC0xMy41LTIuNy0xNi40LTguMWgtMC42djMwLjRDOTM1LjUsNzU5LDkzNS4xLDc1OS41LDkzNC4zLDc1OS41eiBNOTUyLjksNzMxLjRoMTEuMgoJCQkJYzUuMiwwLDkuMi0xLjUsMTEuOS00LjVjMi44LTMsNC4yLTcuMSw0LjItMTIuNHYtMzYuNmMwLTUuMy0xLjQtOS40LTQuMi0xMi40Yy0yLjgtMy02LjgtNC41LTExLjktNC41aC0xMS4yCgkJCQljLTUuMiwwLTkuNCwxLjQtMTIuNiw0LjJjLTMuMiwyLjgtNC44LDYuOC00LjgsMTEuOXYzOC4yYzAsNS4yLDEuNiw5LjIsNC44LDExLjlDOTQzLjUsNzMwLDk0Ny43LDczMS40LDk1Mi45LDczMS40eiIvPgoJCQk8cGF0aCBjbGFzcz0ic3QxIiBkPSJNMTAwNC44LDc1OC42Yy0wLjksMC0xLjQtMC40LTEuNC0xLjJ2LTEuOWMwLTAuOCwwLjUtMS4yLDEuNC0xLjJoNC41YzQuMSwwLDcuMS0wLjgsOC44LTIuMgoJCQkJYzEuNy0xLjUsMy0yLjYsMy44LTMuM2MwLjgtMC43LDEuNy0yLDIuNy00YzEtMiwxLjYtMy4zLDEuOS00YzEuOS00LjEsMy03LjIsMy42LTkuMmgtMS42Yy0wLjgsMC0xLjQtMC41LTEuNy0xLjRsLTI2LjQtNzIuMQoJCQkJYy0wLjMtMC45LDAtMS40LDAuOS0xLjRoMi41YzAuNywwLDEuMiwwLjUsMS42LDEuNGwyNS4zLDY5aDAuNmwyNS4zLTY5YzAuMy0wLjksMC44LTEuNCwxLjYtMS40aDIuNWMwLjksMCwxLjIsMC41LDAuOSwxLjQKCQkJCWwtMjYuNCw3Mi4xYy0zLjIsOS4yLTUuNiwxNS4xLTcuMywxNy44Yy00LjQsNi45LTEwLjcsMTAuNC0xOC42LDEwLjVIMTAwNC44eiIvPgoJCQk8cGF0aCBjbGFzcz0ic3QyIiBkPSJNMTEzMC42LDczNS44aC01MC4zYy0xLjgsMC0yLjYtMC45LTIuNi0yLjZ2LTk0LjVjMC0xLjgsMC45LTIuNiwyLjYtMi42aDkuOGMxLjgsMCwyLjYsMC45LDIuNiwyLjZ2ODIuMQoJCQkJYzAsMSwwLjYsMS42LDEuOSwxLjZoMzZjMS44LDAsMi42LDAuOSwyLjYsMi44djguMUMxMTMzLjMsNzM0LjksMTEzMi40LDczNS44LDExMzAuNiw3MzUuOHoiLz4KCQkJPHBhdGggY2xhc3M9InN0MiIgZD0iTTExNDYuOCw2NDMuNXYtMTQuMWMwLTEuNywwLjgtMi41LDIuNS0yLjVoMTAuMWMxLjcsMCwyLjUsMC44LDIuNSwyLjV2MTQuMWMwLDEuOC0wLjgsMi42LTIuNSwyLjZoLTEwLjEKCQkJCUMxMTQ3LjYsNjQ2LjEsMTE0Ni44LDY0NS4yLDExNDYuOCw2NDMuNXogTTExNDYuOCw3MzMuMXYtNzMuOGMwLTEuOCwwLjgtMi42LDIuNS0yLjZoOS45YzEuOCwwLDIuNiwwLjksMi42LDIuNnY3My44CgkJCQljMCwxLTAuMiwxLjctMC41LDIuMWMtMC40LDAuNC0xLDAuNS0xLjksMC41aC05LjlDMTE0Ny42LDczNS44LDExNDYuOCw3MzQuOSwxMTQ2LjgsNzMzLjF6Ii8+CgkJCTxwYXRoIGNsYXNzPSJzdDIiIGQ9Ik0xMjExLDczMS45aC03Yy03LjQsMC0xMy4yLTIuMS0xNy4xLTYuM2MtNC00LjItNi0xMC4xLTYtMTcuOHYtMjcuMWMwLTcuNywyLjEtMTMuNiw2LjQtMTcuOAoJCQkJYzQuMi00LjIsMTAuMS02LjMsMTcuNy02LjNoMzQuN2MxLjksMCwyLjgsMC45LDIuOCwyLjZ2NzYuOGMwLDcuNS0yLjEsMTMuNC02LjQsMTcuNmMtNC4zLDQuMi0xMC4yLDYuMy0xNy44LDYuM2gtMjkuMgoJCQkJYy0xLjgsMC0yLjYtMC44LTIuNi0yLjV2LTguMWMwLTEuOCwwLjktMi42LDIuNi0yLjZoMjYuOGM3LjUsMCwxMS4zLTMuOCwxMS4zLTExLjV2LTExLjhoLTAuNgoJCQkJQzEyMjQuMSw3MjkuMSwxMjE4LjgsNzMxLjksMTIxMSw3MzEuOXogTTEyMjcuMyw3MDUuNXYtMzQuMWMwLTEtMC42LTEuNi0xLjctMS42aC0xOC41Yy03LjMsMC0xMSwzLjgtMTEsMTEuNXYyNS43CgkJCQljMCw3LjcsMy43LDExLjUsMTEsMTEuNWg3LjRDMTIyMyw3MTguNSwxMjI3LjMsNzE0LjIsMTIyNy4zLDcwNS41eiIvPgoJCQk8cGF0aCBjbGFzcz0ic3QyIiBkPSJNMTI3NC4zLDczNS44aC05LjhjLTEuOCwwLTIuNi0wLjktMi42LTIuNlY2MjkuNGMwLTEuOCwwLjktMi42LDIuNi0yLjZoOS44YzEuOCwwLDIuNiwwLjksMi42LDIuNnYzNS41aDAuNgoJCQkJYzIuNS01LjUsNy43LTguMiwxNS43LTguMmg2LjhjNy41LDAsMTMuMywyLjEsMTcuNCw2LjJjNCw0LjEsNiwxMC4xLDYsMTcuOHY1Mi40YzAsMS44LTAuOSwyLjYtMi44LDIuNmgtOS44CgkJCQljLTEuOCwwLTIuNi0wLjktMi42LTIuNnYtNTEuOGMwLTcuNy0zLjgtMTEuNS0xMS4zLTExLjVoLTcuM2MtOC41LDAtMTIuNyw0LjQtMTIuNywxMy4ydjUwLjEKCQkJCUMxMjc2LjksNzM0LjksMTI3Niw3MzUuOCwxMjc0LjMsNzM1Ljh6Ii8+CgkJCTxwYXRoIGNsYXNzPSJzdDIiIGQ9Ik0xMzQ0LjQsNjY5LjhoLTcuNGMtMSwwLTEuNy0wLjItMi4xLTAuNWMtMC40LTAuNC0wLjUtMS0wLjUtMS45di04LjFjMC0xLjgsMC45LTIuNiwyLjYtMi42aDcuNAoJCQkJYzEsMCwxLjYtMC41LDEuNi0xLjZ2LTE0YzAtMS44LDAuOS0yLjYsMi44LTIuNmg5LjhjMS44LDAsMi42LDAuOSwyLjYsMi42djE0YzAsMSwwLjYsMS42LDEuNywxLjZoMTQuNGMxLjksMCwyLjgsMC45LDIuOCwyLjYKCQkJCXY4LjFjMCwxLjctMC45LDIuNS0yLjgsMi41aC0xNC40Yy0xLjEsMC0xLjcsMC41LTEuNywxLjZ2MzkuOWMwLDcuNSwzLjksMTEuMywxMS42LDExLjNoNmMxLjksMCwyLjgsMC45LDIuOCwyLjZ2OC4xCgkJCQljMCwxLjctMC45LDIuNS0yLjgsMi41aC04LjRjLTcuNywwLTEzLjYtMi4xLTE4LTYuMmMtNC4zLTQuMS02LjUtMTAtNi41LTE3LjV2LTQwLjZDMTM0NS45LDY3MC40LDEzNDUuNCw2NjkuOCwxMzQ0LjQsNjY5Ljh6Ii8+CgkJPC9nPgoJPC9nPgoJPGc+CgkJPGc+CgkJCTxwYXRoIGNsYXNzPSJzdDEiIGQ9Ik0xMDE0LjksNDU2LjZMNzUzLjQsMjE5bDcuOCw1NS41YzEyLjEsODYuNiw3NiwxNTcuMSwxNjEuMiwxNzcuMmw4NC41LDIwLjFjNC45LDEuMSw5LjctMS45LDEwLjgtNi44CgkJCQlDMTAxOC4zLDQ2Mi4xLDEwMTcuMiw0NTguNywxMDE0LjksNDU2LjZ6Ii8+CgkJPC9nPgoJCTxnPgoJCQk8cGF0aCBjbGFzcz0ic3QxIiBkPSJNOTkzLjUsNTA0LjdsLTEyNC45LDg1LjZsNi42LTIzLjNjMTAuMi0zNiw0MS41LTYyLjMsNzguOC02NS45bDM3LjEtMy42YzIuMS0wLjIsNCwxLjUsNC4yLDMuNgoJCQkJQzk5NS40LDUwMi4zLDk5NC44LDUwMy44LDk5My41LDUwNC43eiIvPgoJCTwvZz4KCQk8Zz4KCQkJPHBhdGggY2xhc3M9InN0MSIgZD0iTTEwMzAuNCw0NjUuMWMxLjEsNC45LDUuOSw3LjgsMTAuOCw2LjhsODQuNS0yMC4xYzg1LjEtMjAuMSwxNDkuMS05MC42LDE2MS4yLTE3Ny4ybDcuOC01NS41bC0yNjEuNSwyMzcuNgoJCQkJQzEwMzAuOCw0NTguNywxMDI5LjcsNDYyLjEsMTAzMC40LDQ2NS4xeiIvPgoJCTwvZz4KCQk8Zz4KCQkJPHBhdGggY2xhc3M9InN0MSIgZD0iTTEwNTIuOCw1MDEuMWMwLjItMi4xLDIuMS0zLjgsNC4yLTMuNmwzNy4xLDMuNmMzNy4zLDMuNiw2OC42LDI5LjksNzguOCw2NS45bDYuNiwyMy4zbC0xMjQuOS04NS42CgkJCQlDMTA1My4yLDUwMy44LDEwNTIuNiw1MDIuMywxMDUyLjgsNTAxLjF6Ii8+CgkJPC9nPgoJCTxnPgoJCQk8Y2lyY2xlIGNsYXNzPSJzdDMiIGN4PSIxMDI0IiBjeT0iNDgzLjMiIHI9IjgwLjciLz4KCQk8L2c+CgkJPGc+CgkJCTxjaXJjbGUgY2xhc3M9InN0MiIgY3g9IjEwMjQiIGN5PSI0ODMuMyIgcj0iNTMuOCIvPgoJCTwvZz4KCTwvZz4KPC9nPgo8L3N2Zz4K" alt="Flappy Light"></a>

## Intalação

 Instale o node-red utilizando o comando

```
npm i -g node-red
```

Copie importe os nós da aplicação
```
[{"id":"dc020f8e.4ef52","type":"arduino in","z":"bdccdfd2.29b1b","name":"Luminosity","pin":"1","state":"ANALOG","arduino":"fb63ac70.6d3ef","x":203.50000762939453,"y":464.2000427246094,"wires":[["c693b61d.ec9ea8","c11c2c0f.0fa3e"]]},{"id":"c693b61d.ec9ea8","type":"ui_gauge","z":"bdccdfd2.29b1b","name":"Luminosidade","group":"50cca53e.e6eb6c","order":0,"width":"6","height":"5","gtype":"gage","title":"Luminosidade","label":"Lux","format":"{{value}}","min":0,"max":"1000","colors":["#00b500","#e6e600","#ca3838"],"seg1":"","seg2":"","x":581.5000152587891,"y":395.00001430511475,"wires":[]},{"id":"72600b67.0bf3a4","type":"socketio-in","z":"bdccdfd2.29b1b","name":"luminosityIO","server":"c3108394.114ce","rules":[{"v":"luminosity"}],"x":236.50001907348633,"y":285.787504196167,"wires":[["981de43a.3f6688"]]},{"id":"981de43a.3f6688","type":"debug","z":"bdccdfd2.29b1b","name":"debug","active":true,"console":"false","complete":"true","x":514.1000099182129,"y":281.600004196167,"wires":[]},{"id":"6d872fe0.6a9cb","type":"socketio-out","z":"bdccdfd2.29b1b","name":"luminosityIO","server":"c3108394.114ce","x":767.5000152587891,"y":523.8000183105469,"wires":[]},{"id":"c11c2c0f.0fa3e","type":"function","z":"bdccdfd2.29b1b","name":"setSocketIOEvent","func":"msg.socketIOEvent = \"luminosity\";\nreturn msg;","outputs":1,"noerr":0,"x":534.1000862121582,"y":480.60012435913086,"wires":[["6d872fe0.6a9cb"]]},{"id":"fb63ac70.6d3ef","type":"arduino-board","z":"","device":"COM3"},{"id":"50cca53e.e6eb6c","type":"ui_group","z":"","name":"CASA","tab":"1d82026d.0ef09e","disp":true,"width":"6"},{"id":"c3108394.114ce","type":"socketio-config","z":"","port":"1550","sendClient":"true","path":"/socket.io","bindToNode":true},{"id":"1d82026d.0ef09e","type":"ui_tab","z":"","name":"Home","icon":"dashboard"}]
```

Vá até a pasta `./client_css/` com o terminal e execute o comando
```
npm install
```
ou
```
yarn install
```

# Como jogar agora?

- Primeiro suba o serviço no node-red com o flow importado
```
node-red
```
- Depois rode o comando:

```
npm start
```
