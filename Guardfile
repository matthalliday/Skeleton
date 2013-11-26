guard 'livereload' do
  watch(%r{\.(css|scss|js|coffee|html|php)})
end

guard 'sass',
  input: 'assets/style/sass',
  output: 'assets/style/compiled',
  style: :compressed,
  all_on_start: true

guard 'coffeescript',
  input: 'assets/script/coffee',
  output: 'assets/script/compiled',
  all_on_start: true,
  bare: true