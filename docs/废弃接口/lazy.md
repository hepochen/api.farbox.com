** lazy (懒人变量) **


| 变量名 | 描述 |
| ----- | --- |
| lazy.has_public_posts | 当前网站是否发布过文章 |
| lazy.has_images |  当前网站是否有图片 |
| lazy.has_files | 当前网站是否有文件 |
| lazy.`<path>` | 返回<path>对应的非私密的文档内容，HTML格式 |
| lazy.raw_`<path>` | 同上，非HTML格式 |
| lazy.is_freshman | 当前登录用户是否是新人 |
| lazy.users_all_sites | sites的列表，当前登录用户的网站列表 |

注1, `lazy.<path>`，比如调用lazy.anything的时候，它会去读取/your-site-folder/anything.md(or .txt .markdown)的文件内容，并返回以HTML格式的文本。如果是lazy.anything__subthing, 它则会去寻找/your-site-folder/anything/subthing.md(or .txt .markdown)。
