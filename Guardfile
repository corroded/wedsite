# A sample Guardfile
# More info at https://github.com/guard/guard#readme

guard 'livereload' do
  watch(%r{templates/.+\.(erb|haml)})
  watch(%r{app/helpers/.+\.rb})
  watch(%r{(public/|app/assets).+\.(js|html)})
  watch(%r{(sass/.+\.sass)}) { |m| m[1] }
  watch(%r{(sass/partials/.+\.sass)}) { |m| m[1] }
end
