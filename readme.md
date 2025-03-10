
## Contents
- [Usage]
- [Node]()
	- [Node.from()]()
	- [Node.hasNode()]()
	- [Node.wrap()]()
	- [Node.is()]()
	- [Node.tag()]()
	- [Node.query()]()
	- [Node.queryAll()]()
	- [Node.LS()]()
	- [Node.Attrs()]()
	- [node.tag]()
	- [node.tagName]()
	- [node.document]()
	- [node.parent]()
	- [node.prevNode]()
	- [node.nextNode]()
	- [node.hidden]()
	- [node.class]()
	- [node.style]()
	- [node.css]()
	- [node.dataset]()
	- [node.attrs]()
	- [node.text]()
	- [node.html]()
	- [node.ls]()
	- [node.all]()
	- [node.prevAll]()
	- [node.nextAll]()
	- [node.vp]()
	- [node.abs]()
	- [node.rel]()
	- [node.box]()
	- [node.scr]()
	- [node.constructor()]()
	- [node.on()]()
	- [node.off()]()
	- [node.once()]()
	- [node.emit()]()
	- [node.dispatch()]()
	- [node.observe()]()
	- [node.show()]()
	- [node.hide()]()
	- [node.toggleDisplay()]()
	- [node.checkVisibility()]()
	- [node.click()]()
	- [node.blur()]()
	- [node.focus()]()
	- [node.scroll()]()
	- [node.scrollBy()]()
	- [node.scrollTo()]()
	- [node.scrollIntoView()]()
	- [node.animate()]()
	- [node.requestFullscreen()]()
	- [node.cssAll()]()
	- [node.matches()]()
	- [node.closest()]()
	- [node.isEqual()]()
	- [node.isSame()]()
	- [node.contains()]()
	- [node.append()]()
	- [node.prepend()]()
	- [node.before()]()
	- [node.after()]()
	- [node.add()]()
	- [node.remove()]()
	- [node.replace()]()

- [ViewPortGeometry]()
	- [node.vp.x]()
	- [node.vp.y]()
	- [node.vp.left]()
	- [node.vp.top]()
	- [node.vp.width]()
	- [node.vp.height]()
- [PageGeometry]()
	- [node.abs.x]()
	- [node.abs.y]()
	- [node.abs.left]()
	- [node.abs.top]()
	- [node.abs.width]()
	- [node.abs.height]()
- [OffsetGeometry]()
	- [node.rel.parent]()
	- [node.rel.x]()
	- [node.rel.y]()
	- [node.rel.left]()
	- [node.rel.top]()
	- [node.rel.width]()
	- [node.rel.height]()
- [ClientGeometry]()
	- [node.box.x]()
	- [node.box.y]()
	- [node.box.left]()
	- [node.box.top]()
	- [node.box.width]()
	- [node.box.height]()
- [ScrollGeometry]()
	- [node.scr.x]()
	- [node.scr.y]()
	- [node.scr.left]()
	- [node.scr.top]()
	- [node.scr.width]()
	- [node.scr.height]()
	- [node.scr.hmax]()
	- [node.scr.vmax]()
	- [node.scr.tx]()
	- [node.scr.ty]()
	- [node.scr.to()]()
	- [node.scr.by()]()
	- [node.scr.intoView()]()

- [NodeLS]()
	- [node.ls.length]()
	- [node.ls.first]()
	- [node.ls.last]()
	- [node.ls.at()]()
	- [node.ls.replace()]()
	- [node.ls.clear()]()
	- [node.ls.slice()]()
	- [node.ls.splice()]()
	- [node.ls.shift()]()
	- [node.ls.pop()]()
	- [node.ls.push()]()
	- [node.ls.unshift()]()
	- [node.ls.reverse()]()
	- [node.ls.sort()]()
	- [node.ls.shuffle()]()
	
- [NodeIterator]()
	- [NodeIterator.from()]()
	- [NodeIterator.of()]()
	- [NodeIterator.wrap()]()
	- [iterator.ls]()
	- [iterator.all]()
	- [iterator.drop()]()
	- [iterator.every()]()
	- [iterator.filter()]()
	- [iterator.find()]()
	- [iterator.flatMap()]()
	- [iterator.forEach()]()
	- [iterator.map()]()
	- [iterator.reduce()]()
	- [iterator.some()]()
	- [iterator.take()]()
	- [iterator.toArray()]()
	- [iterator.count()]()
	- [iterator.depth()]()
	- [iterator.texts()]()
	- [iterator.htmls()]()
	- [iterator.on()]()
	- [iterator.off()]()
	- [iterator.once()]()
	- [iterator.emit()]()
	- [iterator.show()]()
	- [iterator.hide()]()
	- [iterator.toggleDisplay()]()
	- [iterator.css()]()
	- [iterator.appendCSS()]()
	- [iterator.removeCSS()]()
	- [iterator.clearCSS()]()
	- [iterator.addClass()]()
	- [iterator.removeClass()]()
	- [iterator.toggleClass()]()
	- [iterator.replaceClass()]()
	- [iterator.clearClasses()]()
	- [iterator.classes()]()
	- [iterator.attr()]()
	- [iterator.removeAttr()]()
	- [iterator.toggleAttr()]()
	- [iterator.clearAttrs()]()
	- [iterator.text()]()
	- [iterator.html()]()
	- [iterator.add()]()
	- [iterator.remove()]()
	- [iterator.indexOf()]()
	- [iterator.includes()]()
	- [iterator.contains()]()
	- [iterator.queryAll()]()
	- [iterator.query()]()
	- [iterator.filterClass()]()
	- [iterator.filterTag()]()
	- [iterator.filterVisible()]()

## class Node
### Node.from(tag)
### Node.hasNode(tag)
### Node.wrap(tag)
### Node.is(node)
### Node.tag(node)
### Node.query(selector)
### Node.queryAll(selector)
### Node.LS(node)
### Node.Attrs(node)
### node.tag
### node.tagName
### node.document
### node.parent
### node.prevNode
### node.nextNode
### node.hidden
### node.class
### node.style
### node.css
### node.dataset
### node.attrs
### node.text
### node.html
### node.ls
### node.all
### node.prevAll
### node.nextAll
### node.vp
### node.abs
### node.rel
### node.box
### node.scr
### node.constructor(config)
### node.on(eventType, listener, options)
### node.off(eventType, listener, options)
### node.once(eventType, listener, options)
### node.emit(eventType)
### node.dispatch(event)
### node.observe(options, listener)
### node.show()
### node.hide()
### node.toggleDisplay()
### node.checkVisibility(options)
### node.click()
### node.blur()
### node.focus()
### node.scroll(... args)
### node.scrollBy(... args)
### node.scrollTo(... args)
### node.scrollIntoView(... args)
### node.animate(... args)
### node.requestFullscreen()
### node.cssAll()
### node.matches(selector)
### node.closest(selector)
### node.isEqual(node)
### node.isSame(node)
### node.contains(node)
### node.append(... nodes)
### node.prepend(... nodes)
### node.before(... nodes)
### node.after(... nodes)
### node.add(config)
### node.remove()
### node.replace(... nodes)

## class ViewPortGeometry
### node.vp.x
### node.vp.y
### node.vp.left
### node.vp.top
### node.vp.width
### node.vp.height

## class PageGeometry
### node.abs.x
### node.abs.y
### node.abs.left
### node.abs.top
### node.abs.width
### node.abs.height

## class OffsetGeometry
### node.rel.parent
### node.rel.x
### node.rel.y
### node.rel.left
### node.rel.top
### node.rel.width
### node.rel.height

## class ClientGeometry
### node.box.x
### node.box.y
### node.box.left
### node.box.top
### node.box.width
### node.box.height

## class ScrollGeometry
### node.scr.x
### node.scr.y
### node.scr.left
### node.scr.top
### node.scr.width
### node.scr.height
### node.scr.hmax
### node.scr.vmax
### node.scr.tx
### node.scr.ty
### node.scr.to(... args)
### node.scr.by(... args)
### node.scr.intoView(... args)

## class NodeLS
### node.ls.length
### node.ls.first
### node.ls.last
### node.ls.at(offset)
### node.ls.replace(... nodes)
### node.ls.clear()
### node.ls.slice(start, end)
### node.ls.splice(start, deleteCount, ... nodes)
### node.ls.shift()
### node.ls.pop()
### node.ls.push(... nodes)
### node.ls.unshift(... nodes)
### node.ls.reverse()
### node.ls.sort(cb)
### node.ls.shuffle()

## class NodeIterator
### NodeIterator.from(iterable)
### NodeIterator.of(... nodes)
### NodeIterator.wrap(tags)
### iterator.ls
### iterator.all
### iterator.drop(limit)
### iterator.every(cb)
### iterator.filter(cb)
### iterator.find(cb)
### iterator.flatMap(cb)
### iterator.forEach(cb)
### iterator.map(cb)
### iterator.reduce(cb, initValue)
### iterator.some(cb)
### iterator.take(limit)
### iterator.toArray()
### iterator.count()
### iterator.depth()
### iterator.texts()
### iterator.htmls()
### iterator.on(eventType, listener, options)
### iterator.off(eventType, listener, options)
### iterator.once(eventType, listener, options)
### iterator.emit(eventType)
### iterator.show()
### iterator.hide()
### iterator.toggleDisplay()
### iterator.css(name, value)
### iterator.appendCSS(name, value)
### iterator.removeCSS(name)
### iterator.clearCSS(name)
### iterator.addClass(... tokens)
### iterator.removeClass(... tokens)
### iterator.toggleClass(token, force)
### iterator.replaceClass(oldToken, newToken)
### iterator.clearClasses()
### iterator.classes()
### iterator.attr(name, value)
### iterator.removeAttr(name)
### iterator.toggleAttr(name, force)
### iterator.clearAttrs()
### iterator.text(text)
### iterator.html(html)
### iterator.add(config)
### iterator.remove()
### iterator.indexOf(value)
### iterator.includes(value)
### iterator.contains(value)
### iterator.queryAll(selector)
### iterator.query(selector)
### iterator.filterClass(token)
### iterator.filterTag(name)
### iterator.filterVisible()
