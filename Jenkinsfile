import java.text.SimpleDateFormat;

def sdf = new SimpleDateFormat("yyyyMMdd-HHmmss");
def version = "1.0.0.";
def type = "DEV";
def build_date = sdf.format(build.getTime());

def build_id = build.properties.environment.BUILD_NUMBER.toString();

def version_number_formatted = version + build_id + "-" + type + "-" + build_date;

build.displayName = version_number_formatted;
