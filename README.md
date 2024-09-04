# unique

Use github.com to store hashing functions, for generate hash from password and verifing it. Use bcrypt library. 



package hash

import (
	"fmt"
	"log"
	"unique"
)

func Hash() {
	r, err := unique.HashPassword("14022014")
	if err != nil {
		log.Fatal(err)
	}
	fmt.Println(r)
}
