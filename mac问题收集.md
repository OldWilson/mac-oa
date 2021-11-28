1. brew 更新错误

   ```sh
   Updating Homebrew...
   /usr/local/Homebrew/Library/Homebrew/version.rb:368:in `initialize': Version value must be a string; got a NilClass () (TypeError)
   	from /usr/local/Homebrew/Library/Homebrew/os/mac/version.rb:26:in `initialize'
   	from /usr/local/Homebrew/Library/Homebrew/os/mac.rb:24:in `new'
   	from /usr/local/Homebrew/Library/Homebrew/os/mac.rb:24:in `version'
   	from /usr/local/Homebrew/Library/Homebrew/os/mac.rb:58:in `prerelease?'
   	from /usr/local/Homebrew/Library/Homebrew/os.rb:21:in `<module:OS>'
   	from /usr/local/Homebrew/Library/Homebrew/os.rb:3:in `<top (required)>'
   	from /System/Library/Frameworks/Ruby.framework/Versions/2.6/usr/lib/ruby/2.6.0/rubygems/core_ext/kernel_require.rb:54:in `require'
   	from /System/Library/Frameworks/Ruby.framework/Versions/2.6/usr/lib/ruby/2.6.0/rubygems/core_ext/kernel_require.rb:54:in `require'
   	from /usr/local/Homebrew/Library/Homebrew/global.rb:37:in `<top (required)>'
   	from /usr/local/Homebrew/Library/Homebrew/brew.rb:23:in `require_relative'
   	from /usr/local/Homebrew/Library/Homebrew/brew.rb:23:in `<main>'
   /usr/local/Homebrew/Library/Homebrew/version.rb:368:in `initialize': Version value must be a string; got a NilClass () (TypeError)
   	from /usr/local/Homebrew/Library/Homebrew/os/mac/version.rb:26:in `initialize'
   	from /usr/local/Homebrew/Library/Homebrew/os/mac.rb:24:in `new'
   	from /usr/local/Homebrew/Library/Homebrew/os/mac.rb:24:in `version'
   	from /usr/local/Homebrew/Library/Homebrew/os/mac.rb:58:in `prerelease?'
   	from /usr/local/Homebrew/Library/Homebrew/os.rb:21:in `<module:OS>'
   	from /usr/local/Homebrew/Library/Homebrew/os.rb:3:in `<top (required)>'
   	from /System/Library/Frameworks/Ruby.framework/Versions/2.6/usr/lib/ruby/2.6.0/rubygems/core_ext/kernel_require.rb:54:in `require'
   	from /System/Library/Frameworks/Ruby.framework/Versions/2.6/usr/lib/ruby/2.6.0/rubygems/core_ext/kernel_require.rb:54:in `require'
   	from /usr/local/Homebrew/Library/Homebrew/global.rb:37:in `<top (required)>'
   	from /usr/local/Homebrew/Library/Homebrew/brew.rb:23:in `require_relative'
   	from /usr/local/Homebrew/Library/Homebrew/brew.rb:23:in `<main>'
   ```

   * 解决方法

     ```sh
     brew update-reset
     ```

     