# 客户端

<div class="alert alert-info">
	SSDB 支持 Redis 网络协议, 所以你可以用 Redis 的客户端来连接 SSDB 服务器. 但是, 使用 SSDB 客户端是最高效的方式.
	<br/><br/>
	所有的 SSDB 客户端 API 都是支持二进制数据的, 二进制数据即是字符串, 字符串就是二进制数据.
</div>

SSDB 源码仓库中, 内置了许多语言的客户端, 这些便是所谓的__官方客户端__. 另外, 还有许多开发者开发的客户端, 也列在这里.

推荐的客户端会被打上星号标记 <span style="color: #cc3;">★</span>.

如果你开发了一个客户端, 希望列在这个页面的话, 请在 GitHub 上 fork [ssdb-docs 项目](https://github.com/ideawu/ssdb-docs), 编辑 ```clients.md```, 然后提交一个 Pull Request.

### C++

---

<table width="100%">
	<tr>
		<td width="15%">内置 <span style="color: #cc3;">★</span></td>
		<td width="15%">ideawu</td>
		<td width="20%">
			<a href="https://github.com/ideawu/ssdb">Repository</a>
		</td>
		<td>
			官方客户端
		</td>
	</tr>
</table>

### [Cpy](https://github.com/ideawu/cpy)

---

<table width="100%">
	<tr>
		<td width="15%">内置 <span style="color: #cc3;">★</span></td>
		<td width="15%">ideawu</td>
		<td width="20%">
			<a href="https://github.com/ideawu/ssdb">Repository</a>
		</td>
		<td>
			官方客户端
		</td>
	</tr>
</table>

<h3>C# .Net</h3>

---

<table width="100%">
	<tr>
		<td width="15%">官方 <span style="color: #cc3;">★</span></td>
		<td width="15%">ideawu</td>
		<td width="20%">
			<a href="https://github.com/ssdb/dotnetssdb">Repository</a>
		</td>
		<td>
			官方客户端
		</td>
	</tr>
</table>

### Go

---

<table width="100%">
	<tr>
		<td width="15%">官方 <span style="color: #cc3;">★</span></td>
		<td width="15%">ideawu</td>
		<td width="20%">
			<a href="https://github.com/ssdb/gossdb">Repository</a>
		</td>
		<td>
			官方客户端
		</td>
	</tr>
</table>

### Java

---

<table width="100%">
	<tr>
		<td width="15%">官方 <span style="color: #cc3;">★</span></td>
		<td width="15%">ideawu</td>
		<td width="20%">
			<a href="https://github.com/ssdb/javassdb">Repository</a>
		</td>
		<td>
			官方客户端
		</td>
	</tr>
	<tr>
		<td width="15%">ssdb4j</td>
		<td width="15%">nutzam</td>
		<td width="20%">
			<a href="https://github.com/nutzam/ssdb4j">Repository</a>
		</td>
		<td>
			又一个SSDB的Java驱动
		</td>
	</tr>
</table>

### Lua

---

<table width="100%">
	<tr>
		<td width="15%">lua-resty-ssdb</td>
		<td width="15%">LazyZhu</td>
		<td width="20%">
			<a href="https://github.com/LazyZhu/lua-resty-ssdb">Repository</a>
		</td>
		<td>
			Lua ssdb client driver for the ngx_lua based on the cosocket API
		</td>
	</tr>
</table>

### NodeJS

---

<table width="100%">
	<tr>
		<td width="15%">官方 <span style="color: #cc3;">★</span></td>
		<td width="15%">ideawu</td>
		<td width="20%">
			<a href="https://github.com/ssdb/nodessdb">Repository</a>
		</td>
		<td>
			官方客户端
		</td>
	</tr>
	<tr>
		<td width="15%">node-ssdb by @hit9</td>
		<td width="15%">hit9</td>
		<td width="20%">
			<a href="https://github.com/eleme/node-ssdb">Repository</a>
		</td>
		<td>
			node-ssdb by @hit9
		</td>
	</tr>
</table>

### PHP

---

<table width="100%">
	<tr>
		<td width="15%">内置 <span style="color: #cc3;">★</span></td>
		<td width="15%">ideawu</td>
		<td width="20%">
			<a href="https://github.com/ideawu/ssdb">Repository</a>
		</td>
		<td>
			官方客户端
		</td>
	</tr>
</table>

### Python

---

<table width="100%">
	<tr>
		<td width="15%">内置 <span style="color: #cc3;">★</span></td>
		<td width="15%">ideawu</td>
		<td width="20%">
			<a href="https://github.com/ideawu/ssdb">Repository</a>
		</td>
		<td>
			官方客户端
		</td>
	</tr>
	<tr>
		<td width="15%">pyssdb</td>
		<td width="15%">ifduyue</td>
		<td width="20%">
			<a href="https://github.com/ifduyue/pyssdb">Repository</a>
		</td>
		<td>
			A SSDB Client Library for Python
		</td>
	</tr>
	<tr>
		<td width="15%">ssdb-py</td>
		<td width="15%">wrongwaycn</td>
		<td width="20%">
			<a href="https://github.com/wrongwaycn/ssdb-py">Repository</a>
		</td>
		<td>
			SSDB Python Client like Redis-Py
		</td>
	</tr>
	<tr>
		<td width="15%">ssdb.py</td>
		<td width="15%">hit9</td>
		<td width="20%">
			<a href="https://github.com/hit9/ssdb.py">Repository</a>
		</td>
		<td>
			SSDB Python Client Library by hit9
		</td>
	</tr>
</table>

### Ruby

---

<table width="100%">
	<tr>
		<td width="15%">ssdb-rb</td>
		<td width="15%">bsm</td>
		<td width="20%">
			<a href="https://github.com/bsm/ssdb-rb">Repository</a>
		</td>
		<td>
			Ruby client library for SSDB
		</td>
	</tr>
</table>

