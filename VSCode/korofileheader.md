<!--
 * @Author: tangdaoyong
 * @Date: 2020-11-18 22:13:25
 * @LastEditors: tangdaoyong
 * @LastEditTime: 2020-11-18 22:16:20
 * @Description: korofileheader使用
-->
# korofileheader

`ctrl+alt+i`或`ctrl+command+i`,添加 文件头 注释
`ctrl+alt+t`或`ctrl+command+t`,添加 函数 注释

```
{
    "git.autofetch": true,
    "files.eol": "\n",
    "todo-tree.tree.showScanModeButton": false,
    "fileheader.customMade": {//此为头部注释
        "Author":"tangdaoyong",
        "Date":"Do not edit",
        "LastEditors":"tangdaoyong",
        "LastEditTime":"Do not edit",
        "Description":"file content"
    },
    "fileheader.cursorMode": {//此为函数注释
    
    },
    "fileheader.configObj": {
        "createFileTime": true,
        "language": {
            "languagetest": {
                "head": "/$$",
                "middle": " $ @",
                "end": " $/"
            }
        },
        "autoAdd": false,// 默认开启自动添加头部注释，当文件没有设置头部注释时保存会自动添加
        "autoAddLine": 100,
        "autoAlready": true,
        "annotationStr": {
            "head": "/*",
            "middle": " * @",
            "end": " */",
            "use": false
        },
        "headInsertLine": {
            "php": 2,
            "sh": 2
        },
        "beforeAnnotation": {
            "文件后缀": "该文件后缀的头部注释之前添加某些内容"
        },
        "afterAnnotation": {
            "文件后缀": "该文件后缀的头部注释之后添加某些内容"
        },
        "specialOptions": {
            "特殊字段": "自定义比如LastEditTime/LastEditors"
        },
        "switch": {
            "newlineAddAnnotation": true
        },
        "supportAutoLanguage": [],
        "prohibitAutoAdd": [
            "json"
        ],
        "prohibitItemAutoAdd": [
            "项目的全称, 整个项目禁止自动添加头部注释, 可以使用快捷键添加"
        ],
        "moveCursor": true,
        "dateFormat": "YYYY-MM-DD HH:mm:ss",
        "atSymbol": [
            "@",
            "@"
        ],
        "atSymbolObj": {
            "文件后缀": [
                "头部注释@符号",
                "函数注释@符号"
            ]
        },
        "colon": [
            ": ",
            ": "
        ],
        "colonObj": {
            "文件后缀": [
                "头部注释冒号",
                "函数注释冒号"
            ]
        },
        "filePathColon": "路径分隔符替换",
        "showErrorMessage": false,
        "wideSame": false,
        "wideNum": 13,
        "CheckFileChange": false,
        "createHeader": true,
        "useWorker": false,
        "typeParam": true,
        "designAddHead": false,
        "headDesignName": "random",
        "headDesign": false
    }
}
```