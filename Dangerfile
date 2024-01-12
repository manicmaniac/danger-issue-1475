filename = "test.txt"
File.read(filename).each_line.with_index(1) do |line, lineno|
  if line.start_with?(" ")
    warn("Do not put whitespaces at the beginning of line.", file: filename, line: lineno)
  end
end
