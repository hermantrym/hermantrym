```golang
package main

import (
	"fmt"
)

type Bio map[string]string

func main() {
	for k, v := range GetBio() {
		fmt.Printf("%+v: %+v\n", k, v)
	}
}

func GetBio() Bio {
	return Bio{
		"- ⚡ Quick bio:":                     "A kind of foodLover-gamer-coder-programmer hybrid",
		"- 🔭 I’m currently working on":      "Dian Nuswantoro University as a Laboran Research Lab",
		"- 🌱 I’m currently research on":     "UX Research, Artificial Intelligence, Machine Learning,
						       Deep Learning --- Sharpening write paper Skills to build
						       a reputation as a researcher (Personal goal)",
		"- 👯 I’m looking to collaborate on": "Python, C++ and CMake related projects",
		"- 🤔 I’m looking for help with":     "Anything related to what I am currently learning 😅",
		"- 💬 Ask me about":                  "C++, C, Python",
		"- 📫 How to reach me:":              "https://hermantrym.live/",
	}
}
```
