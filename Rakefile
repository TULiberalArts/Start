require 'html-proofer'

task default: [:test]

task :test do
  HTML::Proofer.new("./_site", {
    :typhoeus => {
      :ssl_verifypeer => false,
      :ssl_verifyhost => 0}
  }).run
end