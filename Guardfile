Bundler.require :default

guard 'shell' do
  watch(/^main\.asciidoc$/) {|m|
    Asciidoctor.convert_file m[0], safe: :safe
  }
end
