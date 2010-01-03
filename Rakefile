
begin
  require 'bones'
rescue LoadError
  abort '### Please install the "bones" gem ###'
end

ensure_in_path 'lib'
require 'pdf_merge'

task :default => 'test:run'
task 'gem:release' => 'test:run'

Bones {
  name  'pdf_merge'
  authors  'Tim Pease'
  email  'tim.pease@gmail.com'
  url  'http://github.com/TwP/pdf_merge'
  version  PdfMerge::VERSION
  ignore_file  '.gitignore'
}

# EOF
