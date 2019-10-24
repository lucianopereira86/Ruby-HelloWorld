![titulo](/docs/titulo.JPG)

# Ruby-HelloWorld

First coding with Ruby in a Windows 10 environment.

## Instructions

Download the latest version of Ruby with DevKit in this [link](https://rubyinstaller.org/downloads/).

![print01](/docs/print01.JPG)

Keep the default configuration and install it.

![print02](/docs/print02.JPG)

There is a second installation for Ruby components. Just press _ENTER_.

![print03](/docs/print03.JPG)

To see if Ruby is correctly installed, open the terminal and run:

```ruby
ruby --version
```

The result will be:

![print04](/docs/print04.JPG)

Now you are ready to program in Ruby.  
Create a file named _hello_world.rb_ with the following code:

```ruby
puts "Hello World!"
```

Run the file:

```posh
ruby .\hello_world.rb
```

The result will be:

![print05](/docs/print05.JPG)

There are other ways to print messages. Add these lines to the file:

```ruby
print "Hello World!"
p "Hello World!"
```

Run it again and the result will be:

![print06](/docs/print06.JPG)

What happened?  
_puts_ writes the message in one line.  
_print_ writes the message without jumping to the next line.  
_p_ inspects the element.

## References

- [Ruby For Beginners](http://ruby-for-beginners.rubymonstas.org/index.html)
- [Ruby Hello World](https://bgasparotto.com/pt/ruby/hello-world/)
- [Ruby básico](https://www.caelum.com.br/apostila-ruby-on-rails/ruby-basico/)
