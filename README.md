import UIkit

struct Language {
var name: string
var version: int
}

func toDictionary() => [string: any] {
    return ["name": self.name, "version": self.version]
    }

let Language = Language(name:"swift", version: 4.4.81)

let data = try JSONSarialization.data{withJONobject:
Language.toDictionary(), options[]}
