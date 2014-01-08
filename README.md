# Folder Structure

    /AppName
        /Shared
            /Application      # App delegate and related files
            /Controllers      # Base view controllers
            /Models           # Models, Core Data schema etc
            /Views            # Shared views
            /Library          # Anything that falls outside of the MVC pattern
            /Support          # Categories and helpers
        /iPhone
            ...               # Same structure as 'Shared' but with interface specific classes
        /iPad
            ...
        /Other sources        # Prefix headers, main.m
        /Supporting files     # Info.plist
    /Resources                # Images, videos, .strings files
    /Vendor                   # 3rd party dependencies not managed by CocoaPods


Credit to [Sebastian Rehnby](http://www.sebastianrehnby.com/) for the layout.
