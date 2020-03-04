package com.view.verify;

import java.nio.file.Files;
import java.nio.file.Path;
import java.nio.file.Paths;

import org.apache.commons.io.FileUtils;

import java.io.File;
import java.io.IOException;

public class ReplaceEAR {
	public static void main(String args[]) {

		String Destination = "C:\\Users\\212787016\\Downloads\\wildfly-8.2.1.Final\\wildfly-8.2.1.Final\\standalone\\deployments\\osm.ear";
		String Source = "C:\\Users\\212787016\\Desktop\\osm.ear";
		File src = new File(Source);
		File dest = new File(Destination);
		try {
			FileUtils.copyFile(src, dest);
		} catch (IOException e) {
			System.out.println("Error");
			e.printStackTrace();
		}
	}

}
