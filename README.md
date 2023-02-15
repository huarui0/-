
# 参考资源
## 词典
  * <details open>
        <summary>
            <i><b>✨ Finder 的 使用技巧<</b></i>
        </summary>
        <ul style="disc">
            <li><a id="use-of-finder-tags"></a>
                <details open>
                    <summary>
                        ✨ ✨ ✨ Finder Tags 的 使用方法 和 技巧 👍
                    </summary>
                    <ul>
                        <li>
                            <details open>
                                <summary>
                                    ✨ 说明 - 标签的原理 和 使用 场景【技巧】
                                </summary>
                                <ul>
                                    <li>
                                        ✨ 标签，可以理解为虚拟文件夹
                                    </li>
                                    <li>
                                        【重点】标签的使用， 实现了  文件夹或文件 与 标签 的 多对多关系，这样，就能 实现 组合 的 查询 与 归类，不用复制文件夹或文件
                                    </li>
                                    <li>比如
                                        <ol type="1">
                                            <li>设置一个标签：<b>最常访问</b></li>
                                            <li>再设置一个标签：<b>✨ ✨ ✨ ✨ ✨</b></li>
                                            <li>还可以再设置一个标签：<b>Python笔记</b></li>
                                            <li>将上述标签，都显示在 左边 侧边栏</li>
                                            <li>建一个文件夹：<b>Python开发笔记</b></li>
                                            <li>将<kbd><b>Python开发笔记</b></kbd>这个文件夹，设置为上述三个标签</li>
                                            <li>这样，点击左边侧边栏相应的标签，就能够，查到，对应的 文件或文件夹了</li>
                                        </ol>
                                    </li>
                                </ul>
                            </details>
                        </li>
                        <li>
                            <details open>
                                <summary>
                                    ✨ 参考
                                </summary>
                                <ul>
                                    <li>【优先】<a href="https://www.youtube.com/watch?v=T0Jj4lUm_p8">How to Add Tags in the Mac OS Finder</a></li>
                                    <li><a href="https://macmyths.com/mac-custom-tag-colors/">How To Add More Custom Tag Colors On a Mac</a></li>
                                </ul>
                            </details>
                        </li>
                        <li>
                            <details open>
                                <summary>
                                    ✨ 添加 Tag 的 方法
                                </summary>
                                <ol type="1">
                                    <li>通过 `Preference` 》 `Tags` 添加</li>
                                    <li>新建文件，保存时，可以设置 Tags，这时 可以 添加 Tag</li>
                                </ol>
                            </details>
                        </li>
                    </ul>
                </details>
            </li>
            <li>
                <details open>
                    <summary>
                        ✨ ✨ ✨ Smart Folder 的 使用方法 和 技巧 👍
                    </summary>
                    <ul>
                        <li>
                            <details open>
                                <summary>
                                    ✨ 说明 - 标签的原理 和 使用 场景【技巧】
                                </summary>
                                <ul>
                                    <li>
                                        ✨ 与标签类似，也可以理解为虚拟文件夹，与标签不同的是，Smart Folder 是 通过 查询条件 得到 的 文件夹，是根据条件 的 动态文件夹
                                    </li>
                                    <li>
                                        ✨ 与 Tags 结合 使用 的 方法 更能<b>体现优势</b>
                                    </li>   
                                </ul>
                            </details>
                        </li>
                        <li>
                            <details open>
                                <summary>
                                    ✨ 参考
                                </summary>
                                <ul>
                                    <li>【优先】<a href="https://www.youtube.com/watch?v=9Lz7jliEvGg&list=PLRVt-3hg7Jl71UDJp34uXmNTWnhBZXtQM&index=1&t=624s">150+ Mac Tips and Tricks - Smart Folder setup</a></li>
                                    <li>【官网】<a href="https://support.apple.com/en-hk/guide/mac-help/mchlp2804/mac">Create or change a Smart Folder on Mac</a></li>
                                </ul>
                            </details>
                        </li>
                        <li>
                            <details open>
                                <summary>
                                    ✨ 添加/设置 Smart Folder 的 方法
                                </summary>
                                <ol type="1">
                                    <li></li>
                                    <li></li>
                                </ol>
                            </details>
                        </li>
                        <li>
                            <details open>
                                <summary>
                                    ✨ Change the criteria for a Smart Folder - 修改 Smart Folder 的 规则【条件】
                                </summary>
                                <ol type="1">
                                    <li>In the Finder  on your Mac, open the Smart Folder.</li>
                                    <li>Begin typing in the folder’s search field, or click the Action pop-up menu , then choose Show Search Criteria. - 即 Action 下拉菜单，选择 显示 搜索 规则【条件】</li>
                                </ol>
                            </details>
                        </li>
                        <li>
                            <details open>
                                <summary>
                                    ✨ 一个例子 - 步骤
                                </summary>
                                <ul>
                                    <li>
                                        ✨ 先从 GitHub 下载 例子：<a href="https://github.com/hackersandslackers/flask-blueprint-tutorial">hackersandslackers/flask-blueprint-tutorial</a>
                                        <ol type="1">
                                            <li>创建一个文件夹
                                                <pre><code>cd /Users/DataProjects/SQLiteSamples/Flask
    mkdir hackersandslackers</code></pre>
                                            </li>
                                            <li>下载 GitHub 项目
                                                <pre><code>cd hackersandslackers
    git clone https://github.com/hackersandslackers/flask-blueprint-tutorial.git</code></pre>
                                            </li>
                                        </ol>
                                    </li>
                                    <li>通过 Finder 打开 文件夹 /Users/DataProjects/SQLiteSamples/Flask/hackersandslackers</li>
                                    <li>右键选中 flask-blueprint-tutorial，将 标签： SQLite3_Flask 、	Python_Flask 添加 到 文件夹</li>
                                    <li>新建 Smart Folder</li>
                                    <li>筛选条件
                                        <pre><code>Kind is Folder
    Any of the flowing are true
        Tags matches SQLite3_Flask
        Tags matches Python_Flask</code></pre>
                                    </li>
                                    <li>这样，就能够实现 智能文件夹满足： 既是：SQLite3_Flask，又是：Python_Flask</li>
                                </ul>
                            </details>
                        </li>
                    </ul>
                </details>
            </li>
            <li>
                <details open>
                    <summary>
                        ✨ ✨ ✨ Folder 文件夹组织 方法 👍
                    </summary>
                    <ul>
                        <li>
                            <details open>
                                <summary>
                                    ✨ 参考
                                </summary>
                                <ul>
                                    <li><a href="https://www.youtube.com/watch?v=FiAwbI7_ekA">The Best iCloud Drive Setup.</a></li>
                                </ul>
                            </details>
                        </li>
                        <li>
                            <details open>
                                <summary>
                                    ✨ 文件夹 组织 的 方法 【之一】
                                </summary>
                                <ol type="1">
                                    <li>从桌面，<kbd>Control</kbd> + <kbd>N</kbd>，打开 Finder</li>
                                    <li>View： as Column</li>
                                    <li>View： Use Groups</li>
                                    <li>View： Group by -> Tags 👉 Tags的用法参见<a href="#use-of-finder-tags">Finder Tags 的 使用方法 和 技巧</a></li>
                                </ol>
                            </details>
                        </li>
                    </ul>
                </details>
            </li>
            <li>
                <details open>
                    <summary>
                        ✨ ✨ ✨ 在Finder 的 当前文件夹 创建 文本文件 的 几种方法和技巧 - Creating a Text File in the Current Finder Directory 👍
                    </summary>
                    <ul>
                        <li>
                            <details open>
                                <summary>
                                    ✨ 参考
                                </summary>
                                <ul>
                                    <li>【优先：首先需要了解】<a href="https://developer.apple.com/library/archive/documentation/LanguagesUtilities/Conceptual/MacAutomationScriptingGuide/index.html#//apple_ref/doc/uid/TP40016239-CH56-SW1">About Mac Scripting</a></li>
                                    <li>【优先：首先需要了解】<a href="https://developer.apple.com/library/archive/documentation/LanguagesUtilities/Conceptual/MacAutomationScriptingGuide/GettoKnowScriptEditor.html#//apple_ref/doc/uid/TP40016239-CH5-SW1">Getting to Know Script Editor</a></li>
                                    <li>【推荐】<i><b><a href="https://www.zhihu.com/question/20883777">为什么 macOS 在 Finder 里不可以新建文本文件？</a></b></i></li>
                                    <li>【推荐：优先】- 这个方法更好！<i><b><a href="https://www.instructables.com/AppleScript-for-creating-a-text-file-in-the-curren/">AppleScript for Creating a Text File in the Current Finder Directory</a></b></i></li>
                                    <li>【不推荐】<i><b><a href="https://www.yundongfang.com/Yun117670.html">在 Finder 中创建文本文件</a></b></i></li>
                                    <li> 【有用的参考，这篇有价值】<i><b><a href="https://apple.stackexchange.com/questions/276813/right-click-for-creating-a-new-document-how">Right-click for Creating a New Document - How?</a></b></i>
                                    </li>
                                    <li><i><b><a href="http://hints.macworld.com/article.php?story=20100509134904820">Create a new file anywhere via an Automator Service</a></b></i>
                                    </li>
                                    <li>【JavaScript 的 方法】<i><b><a href="https://medium.com/hackernoon/javascript-for-automation-in-macos-3b499da40da1">Javascript for Automation in macOS</a></b></i>
                                </ul>
                            </details>
                        </li>
                        <li>
                            <details open>
                                <summary>
                                    ✨ 在 Finder 中 快速 创建 文本文件 的 方法和步骤
                                </summary>
                                <ul style="disc">
                                    <li>
                                        <details open>
                                            <summary>
                                                ✨ 作为 Finder 自定义 工具栏 中 的 项
                                            </summary>
                                            <ol type="i">
                                                <li>在 Mac 上打开 Automator 应用程序 - Apple Automator App
                                                    <ol type="1">
                                                        <li>Command + F 搜索 Automator - 可以有其他方法，如Application中直接打开</li>
                                                        <li>在 <kbd>Choose a type for your document</kbd> 界面，选择 <kbd>Application</kbd> </li>
                                                        <li>使用搜索功能并搜索“AppleScript” - 也可以在搜索栏中搜索“run”</li>
                                                        <li>然后双击，或将 Run AppleScript 操作拖放到右侧的工作流程中</li>
                                                    </ol>
                                                </li>
                                                <li>编写 AppleScript 脚本：
                                                   <ol type="1">
                                                       <li>脚本1: 自动创建 文本文件： untitled n【n 代表文件序号，无法自定义文件名称】：
                                                           <pre><code>on run {input, parameters}
        <br>
        tell application "Finder"
        set selection to make new file at (get insertion location)
        end tell
        <br>
        return input
    end run</code></pre>
                                                       </li>
                                                       <li>脚本2: 创建 可自定义文件名称，并带有 <kbd>.txt</kbd>扩展名：
                                                           <pre><code>-- Create text file in current Finder folder with a dialog.
    <br>
    tell application "Finder"
        try
            display dialog "name of doc please (without the .txt thing)" default answer ""
            set fileName to the text returned of result
            if length of fileName = 0 then
                return 0
            end if
            set fileExt to ".txt"
            set thisFolder to the target of the front window as alias
            set newFile to fileName & fileExt
            <br>
            make new file at thisFolder with properties {name:newFile, file type:"TEXT", creator type:"ttxt"}
        on error errMsg
            display dialog (errMsg)
        end try
    end tell</code></pre>
                                                       </li>
                                                       <li>脚本3: 创建 可自定义文件名称，并带有 <kbd>.txt</kbd>扩展名，同时，进行编辑：
                                                           <pre><code>on run
        my createNewTextFile()
    end run
    <br>
    <br>
    on createNewTextFile()
    <br>
        tell application "Finder"
            activate
            set the currentFolder to (folder of the front window as alias)
        end tell
    <br>
        tell me
            activate
            set fileName to ""
            repeat while fileName = ""
                display dialog "Save As:" with title "Create New Text File Here" default answer fileName buttons {"Cancel", "OK"} default button 2
                set fileName to text returned of the result
            end repeat
            if fileName ends with ".txt" then
                set newTextFile to POSIX path of currentFolder & fileName
            else
                set newTextFile to POSIX path of currentFolder & fileName & ".txt"
            end if
    <br>
        end tell
    <br>
        tell application "Finder"
            set itExists to (exists newTextFile as POSIX file)
        end tell
    <br>
        tell me
            activate
            if itExists is false then
                try
                    do shell script "touch \"" & newTextFile & "\"; open \"" & newTextFile & "\""
                on error
                    display dialog "Cannot create the \"" & newTextFile & "\" file at this location!..." with title "Cannot Create File" buttons {"OK"} default button 1 with icon stop
                end try
            else
                display dialog "The \"" & newTextFile & "\" file already exists!..." with title "File Already Exists" buttons {"OK"} default button 1 giving up after 5
                my createNewTextFile()
            end if
        end tell
    <br>
    end createNewTextFile</code></pre>
                                                       </li>
                                                    </ol>
                                                </li>
                                                <li>【必要】脚本编写好后，一定要点击 编译【工具栏上的 锤子 按钮】，看是否有错误。
                                                <li>保存为 Mac OS App：
                                                   <ol type="1">
                                                       <li>在左上角的 文件名称栏中，点击脚本 App 的名称 Untitled.app(Application)</li>
                                                       <li>在下拉列表中，现将文件名称更改为 合适的名称，如 CreateNewTxtFile.app，接着更改保存的文件夹位置，默认的位置为：<pre><code>iCloud Drive/Automator</code></pre>
                                                       </li>
                                                       <li>退出 Automator App，如有提示，选择 保存</li>
                                                   </ol>
                                               </li>
                                               <li>生成 Mac OS 的 Application 应用
                                                   <ol type="1">
                                                       <li>转到 Mac 上的 Finder 并导航到要在其中 创建新文本文件【本例中为 CreateNewTxtFile.app】 的文件夹或目录</li>
                                                       <li>将 刚创建的 脚本 App 拷贝 到 Application 目录中</li>
                                                   </ol>
                                               </li>
                                               <li>将 创建的 App 添加 到 Finder 的 自定义 工具栏 中：
                                                   <ol type="1">
                                                       <li>转到 Mac 上的 Finder 并导航到要在其中 创建新文本文件【本例中为 CreateNewTxtFile.app】 的文件夹或目录</li>
                                                       <li>按住 <kbd>Command</kbd> 键的同时，用触控键盘，将 App 拖放到 Finder 的 工具栏中</li>
                                                   </ol>
                                               </li>
                                               <li>在 当前文件夹中创建 文本文件：
                                                   <ol type="1">
                                                       <li>打开 Finder， 转到 要创建文本文件的 文件夹 中， 点击之前 创建 的 工具栏上的 CreateNewTxtFile  命令，即可创建 需要的 文本文件</li>
                                                   </ol>
                                               </li>
                                            </ol>
                                        </details>
                                    </li>
                                    <li>
                                        <details open>
                                            <summary>
                                                ✨ 作为 Finder 菜单中 的 服务项
                                            </summary>
                                            <ol type="i">
                                                <li>在 Mac 上打开 Automator 应用程序 - Apple Automator App
                                                    <ol type="1">
                                                        <li>Command + F 搜索 Automator - 可以有其他方法，如Application中直接打开</li>
                                                        <li>在 <kbd>Choose a type for your document</kbd> 界面，选择 <kbd>Quick Action - 快速操作</kbd> </li>
                                                        <li>使用搜索功能并搜索“AppleScript” - 也可以在搜索栏中搜索“run”</li>
                                                        <li>然后双击，或将 Run AppleScript 操作拖放到右侧的工作流程中</li>
                                                    </ol>
                                                </li>
                                                <li>编写 AppleScript 脚本：
                                                   <ol type="1">
                                                       <li>脚本1: 自动创建 文本文件： untitled n【n 代表文件序号，无法自定义文件名称】：
                                                           <pre><code>on run {input, parameters}
        <br>
        tell application "Finder" to make new file at (the target of the front window) as alias
        <br>
        return input
    end run</code></pre>
                                                       </li>
                                                    </ol>
                                                </li>
                                                <li>保存为 Quick Action：
                                                   <ol type="1">
                                                       <li>点击 关闭 按钮，退出 Automator</li>
                                                       <li>在 弹出的 窗口 中，在 Save Quick Action as ，输入 Quick Action 的 名称，如 mknewtxtfile</li>
                                                       <li>点击 Save，保存 Quick Action
                                                   </ol>
                                               </li>
                                               <li>在 当前文件夹中创建 文本文件：
                                                   <ol type="1">
                                                       <li>现在转到 Mac 上的 Finder 并导航到要在其中创建新文本文件的文件夹或目录，然后下拉“Finder”菜单并转到“服务”，然后选择之前创建的 快捷操作：“mknewtxtfile”</li>
                                                       <li>将创建一个新的空白文本文件，名为“无标题”</li>
                                                       <li>您可以在 Finder 中的任何位置使用此快速操作来立即生成新的文本文件。</li>
                                                   </ol>
                                               </li>
                                            </ol>
                                        </details>
                                    </li>
                                </ul>        
                            </details>
                        </li>
                    </ul>
                </details>
            </li>
        </ul>
    </details>

----
## 词根词缀查询
  * [Merriam-Webster](https://merriam-webster.com/dictionary)
    + 方法
      - 词根直接查，词缀 加 `-` 符号，前缀加后面，后缀加前面
## 词源查询
  * Collins - <a href="https://www.collinsdictionary.com/dictionary/english">英文</a> ｜ <a href="https://www.collinsdictionary.com/zh/dictionary/english">中文</a>
    + 查词源
      - 查找单词，然后，浏览到 Word origin
    + 查派生词
      - 查找单词，然后，浏览到 Derived forms
    + 查例句
      - 查找单词，然后，浏览到 Example sentences
## 权威词典
  * 英文词典
    + [朗文当代英语词典第5版.mdx](http://www.yunpangou.com/114954599903754240)<br>
